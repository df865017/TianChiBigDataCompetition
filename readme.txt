2015 ����Ͱ���ش����ݾ���(���6��)
1.
��1��data_process.py
raw_file_path
split_file(filtered_file_path, SEPERATEDAY, BEGINDAY)

tianchi_mobile_recommend_train_item.csv

�ָ�����  �ָ�Ϊѵ�����Ͳ��Լ�
    train_file_path = "train_" + raw_file_path
    validation_file_path = "validation_" + raw_file_path
    all_file_path = "all_" + raw_file_path

    t_train = open("temp_" + train_file_path, 'w')
    t_validation = open("temp_" + validation_file_path, 'w')
    t_all = open("temp_" + all_file_path, 'w')

��2��extract_items_features.py
��ȡ��Ʒ����
ѵ����������
train_file_path = "test_item.csv"
ѵ�����ݺ�����
extract_items_features(train_file_path)

��3��extract_users_features.py
��ȡ�û����� �� UIƥ������


