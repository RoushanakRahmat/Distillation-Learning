# Distillation-Learning
Distillation Learning — Teacher Student Model — TensorFlow Tutorial —Image Classification
Full post can be found on my Medium blog: https://medium.com/@roushanakrahmat/distillation-learning-tensorflow-tutorial-478d743d2450

What is a Distillation Learning?
Distillation learning is a type of machine learning approach that involves using a small, efficient model (the “student” model) to learn from a larger, more complex model (the “teacher” model). The student model is trained to replicate the output of the teacher model as closely as possible, using the output of the teacher model as a supervision signal.

The goal of distillation learning is to transfer knowledge from the teacher model to the student model, so that the student model can perform the same task as the teacher model but with a smaller size and faster inference speed.

Here is a simple example of how you might implement distillation learning in Python using the TensorFlow library.
