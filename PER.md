# Prioritized Experience Replay

[`link`](https://arxiv.org/abs/1511.05952)

�� ���� 'Prioritized Experience Replay'�� ���� ���Դϴ�. (���� PER)

1. PER�� �߿��� transition�� �� ���� ���ø��ϰ� �� ȿ�������� �н��ϱ� ���� Replay memory �˰�����.
2. Experience replay�� transition���� ������踦 ���ְ�, ����� ������� �� �� �̻� ����� �� �ְ� ����.
3. TD-error�� �켱������ �����ϴ� �� ���� ����� ������.
4. �� ū TD-error�� ������ transition�� ��Ʈ��ũ ������Ʈ�� �־ �� 'surprising'�ϰ� ���� �Ұ����� transition��.
5. PER�� �����ϴ� ����� Ranked-base�� Stochastic-base�� ����.
6. Ranked-base�� ��ü Replay memory�� ���� sweep�� ���ϱ� ���ؼ�, ������ ���ø� �Ǵ� transition�� ���ؼ��� TD-error�� ������Ʈ ��. �� ��� TD-error�� �������ٸ� �ٽ� ���ø����� ���� �� ����. ���� stochastic�� reward(noise spike)�� ���ؼ��� �ΰ���. �� ���, �� ����� ���� ���ÿ� ���ؼ��� ������ �����ְ� ���������� �� ������ ����.
7. Ranked-base�� ������ �ذ��ϱ� ���ؼ� Sumtree��� ����Ʈ�� ������ �̿��Ͽ� transition�� �����ϰ� ���ø���.
8. PER�� �������� �ʴ� ������� expected value�� ������ �����ϱ� ������ Bias�� ����.
9. �� Bias�� �������ֱ� ���ؼ� Importance-sampling weights�� �����.
