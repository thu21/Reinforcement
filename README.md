
##
### Question 1 - Value Iteration           
Tính,ước lượng k-step của các giá trị tối ưu Kv.
Tìm các trạng thái, khả năng và phần thường cho các hành động tiếp theo. computeActionFromValues (state): tính toán hành động tốt nhất theo hàm giá trị được cung cấp bởi giá trị tự. computeQValueFromValues (state, action) trả về giá trị Q của cặp (state, action) được cung cấp bởi hàm giá trị do self.values cung cấp.

### Question 2 - Bridge Crossing Analysis
Thay đổi các tham số agentDiscount và agentNoise để MDP đưa ra phương án tối ưu giúp agent qua cầu.
### Question 3 - Policies
Thay đổi các tham số agentDiscount và agentNoise để MDP đưa ra phương án tối ưu giúp agent qua cầu. 

### Question 4 - Q-Learning
Viết Q-learning agent, nó thực hiện rất ít việc xây dựng môi trường từ trước, mà thay vào đó học bằng cách thử và sai từ các tương tác với môi trường thông qua phương pháp cập nhật (state, action, nextState, reward) getQValue(state, action) trả về giá trị Qvalue. computeValueFromQValues() Tính toán giá trị lớn nhất của Qvalue computeActionFromQValues() Tính toán hành động tốt để thực hiện trong trạng thái

### Question 5 - Epsilon Greedy
Epsilon-greedy giúp chọn những hành động ngẫu nhiên trong một khoảng thời gian epsilon hoặc tuân theo các giá trị Q tốt nhất hiện tại .Sử dụng hàm flipcoin để chọn ngẫu nhiên hành động hoặc sẽ sử dụng Q tốt nhất. Và viết hàm cập nhật Q-value cho trạng thái và hành động.

### Question 6 - Bridge Crossing Revisited
Không thể tìm đường đi tối ưu vì epsilon quá nhỏ (50 episode), cần khoảng lớn hơn để tìm ra đường đi.

### Question 8 - Approximate Q-Learning
Viết hàm Approximate Q-learning để tìm các trọng số đặc tính của các trạng thái theo công thức đã cho.


