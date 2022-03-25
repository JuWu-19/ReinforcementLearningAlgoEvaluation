## Course project of Advanced Machine Learning MICRO-570

We study the theory and mechanism of two reinforcement
learning algorithms, A2C and PPO2 and their application for
multiple tasks e.g., Cart pole pendulum and lunar landing task.
To do so, we build up a pipeline able to train and manage
our models and environments. 


From the experimental results
obtained, we compute multiple reliability metrics to be able
to lead a discussion about the performance evaluation of the
algorithms. \
<img src="https://user-images.githubusercontent.com/58901415/160098624-97d4982c-d80a-4e0b-b442-2387911759c3.png" width="46%" height="46%" />   
From the above statistics tables, we can observe that A2C and PPO2 have the similar
ranks of short-term and long-term risks across time but
risks of PPO2 have less variance than that of A2C, which
means that they have the similar average performance for
the worst-case scenarios on different tasks. However, PPO2
is more stable than A2C in this case across different tasks
and runs with various settings. We can also see that PPO2
has better reliability performance than A2C with respect to
dispersion across time and risk across runs, which infers that
A2C has the larger average variance of performances and
the worse average final performance across the training runs
across training runs under different tasks. But A2C has better
dispersion across time than PPO2, which means A2C has the
smaller distribution for differential of training curves.
