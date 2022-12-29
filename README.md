# 
Chatbot đặt chỗ nhà hàng sử dụng DRL

Chatbot sử dụng Deep Q Network để tương tác với người dùng tiến hành đặt chỗ nhà hàng
theo yêu cầu của người dùng
Chatbot này không sử dụng ngôn ngữ tự nhiên

Data:
Data sử dụng cho chatbot được lấy ngẫu nhiên từ 15 nhà hàng ở New York. Yêu cầu của người dùng 
được tạo ngẫu nhiên từ dataset và số slot cũng được tạo ngẫu nhiên. Tất cả các data được tạo 
có thể xem ở file gen_data_for_chatbot.ipynb

Dependencies:
Python >= 3.5
Keras >= 2
numpy
Tensorflow >= 1.14

Thay đổi tham số:
Có thể thay đổi các tham số quan trọng trong file constants.json. 
Trong đó có số lần chạy: num_ep_run
Đường dẫn lưu weights của model: load_weights_file_path
Sử dụng DQN hoặc DDQN: vanilla
Sử dụng mô phỏng người dùng hoặc người dùng thật: user_sim

Sử dụng chatbot:
Chạy file python train.py
Có thể dùng weights có sẵn hoặc train lại từ đầu
Chạy file test python test.py và xem kết quả

Tham khảo
Project tham khảo từ https://github.com/maxbren/GO-Bot-DRL

