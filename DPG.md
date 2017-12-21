# Deterministic Policy Gradient Algorithms

[`link`](http://proceedings.mlr.press/v32/silver14.pdf)

�� ���� 'deterministic policy gradient algorithm'�� ���� ���Դϴ�.

1. Deterministic policy gradient�� ��Ƽ����� ȯ���� ��ȭ�н��� ���� ��ȵǾ���.
2. Stochastic policy gradient�ϰ�� �ٸ��� deterministic policy gradient�� exploration�� ������ �����ϱ� ���� off-policy actor critic�� �����.
3. Determinisitc policy  ![equation](https://latex.codecogs.com/gif.latex?a%20%3D%20%5Cmu_%5Ctheta%20%28s%29)
4. Stochastic policy gradient�� action spaces�� state spaces�� �����Ͽ�����, determinisitc policy gradient ���� ��쿡�� state spaces �� ������.
5. ū ������ action space�� ���ؼ� stochastic policy gradient�� ����ϴ� ���� deterministic policy gradient�� ����ϴ� �ͺ��� �� ���� ���� ����� �ʿ���.
6. �� ���� Q���� �̺��ϴ� ���� �ƴϰ�, Q���� mu�� ���� �̺��Ͽ� �����ִ� ������� �ٲ� �����.
7. Deterministic Policy Gradient Theorem�� ������ ��ư ������ Policy Gradient Theorem�̶� ���� ����ϰ� ������.
8. Stochastic off-policy actor-critic �˰����� ����ϱ� ������, actor�� critic ��� Importance Sampling�� ����ؾ���. ������ deterministic policy gradient���� ��쿡�� action�� �����ϴ� ���� �������� ������ actor���� Importance Sampling�� ���� �� ����. ���� critic������ Q-learning�� ����ϹǷν� Importance sampling�� ����.