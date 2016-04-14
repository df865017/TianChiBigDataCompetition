2015 阿里巴巴天池大数据竞赛(暑假6月)
1.
（1）data_process.py
raw_file_path
split_file(filtered_file_path, SEPERATEDAY, BEGINDAY)

tianchi_mobile_recommend_train_item.csv

分割数据  分割为训练集和测试集
    train_file_path = "train_" + raw_file_path
    validation_file_path = "validation_" + raw_file_path
    all_file_path = "all_" + raw_file_path

    t_train = open("temp_" + train_file_path, 'w')
    t_validation = open("temp_" + validation_file_path, 'w')
    t_all = open("temp_" + all_file_path, 'w')

（2）extract_items_features.py
提取商品特征
训练数据名：
train_file_path = "test_item.csv"
训练数据函数：
extract_items_features(train_file_path)

（3）extract_users_features.py
提取用户特征 和 UI匹配特征


