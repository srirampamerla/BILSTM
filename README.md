# GRU- Gated Recurrent Units

GRU: Combines LSTM's gates into update and reset gates, simplifying the architecture.

![image](https://github.com/user-attachments/assets/d3cf79d3-ce82-4693-b81c-56e4a0fdbec9)

Reduced Complexity: LSTMs have two gates (forget and input) to control the flow of information. GRUs, on the other hand, have only two gates:

Reset Gate: Determines how much of the past information should be forgotten.   

Update Gate: Controls how much of the past information should be passed to the next time step.  

This simpler structure makes GRUs easier to train and computationally less expensive.   

Improved Performance: Despite their simpler architecture, GRUs have shown comparable or even better performance than LSTMs in many tasks, particularly in tasks with shorter sequences.

Vanishing Gradients: Like LSTMs, GRUs also help mitigate the vanishing gradient problem, allowing them to capture long-range dependencies in sequential data.

GRU: Comparable to LSTM but faster and smaller in size.

![image](https://github.com/user-attachments/assets/d3d82ca5-edfa-45b4-9c06-2f865ddfd7c7)


![image](https://github.com/user-attachments/assets/114af05f-416f-415d-8e12-0d99f9fc04df)

# Implementation


![image](https://github.com/user-attachments/assets/66b84122-d4df-471c-8fba-77cf33b9d471)


# BILSTM- Bidirectional LSTMs 

BiLSTM: Extends LSTM by processing sequences forward and backward for better context.

By combining the outputs of both forward and backward LSTMs, BiLSTMs can capture contextual information from both past and future elements in the sequence. This provides a more comprehensive understanding of the sequence as a whole.


![image](https://github.com/user-attachments/assets/5f42764f-5f28-48f1-a318-b2ce7b0fc678)


Enhanced Performance: BiLSTMs often outperform unidirectional LSTMs in various NLP tasks due to their ability to leverage richer contextual information.


![image](https://github.com/user-attachments/assets/f766df78-46d6-4ade-911c-73657132cc03)

# Implementation


![image](https://github.com/user-attachments/assets/1e36e41f-88da-4346-a326-63b577ed906f)


![image](https://github.com/user-attachments/assets/f479529d-f833-4e7d-af40-4cd68b908ecf)




