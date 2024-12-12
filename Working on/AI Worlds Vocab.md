
# Transformer
名为Transformer的新型神经网络，基于注意力的编码器-解码器构建的
The encoder output is a continous vector representation of the inputs

The decoder get this continous vector, 并且逐步生成单一输出，并且还会生成前一个输出
- Inputs part
	- Inputs Embedding
		- 把输入每个单词转换成向量
	- position embedding
		- inputs embedding + positional encoding => positional input embeddings
		- 正弦和余弦函数
			- 奇数time step 正弦
			- 偶数time step 余弦
	- Encoder layer
		- 将所有序列map continous vector包含了整个序列的学习信息


## 什么注意力机制

## 注意力机制和RNN差别
注意力机制不受短时记忆的影响， 注意力机制在理论上，计算资源充足的情况下，具有无限的参考窗口，可以在生成文本的时候使用整个content的上下文

分开embedding，get query, key, value vectors
![](assets/AI%20Worlds%20Vocab/image-20241010113534825.png)

![](assets/AI%20Worlds%20Vocab/image-20241010113555453.png)

然后开平方缩小和稳定scores

## 多头注意力机制
## 自注意力
允许模型将输入中的单词与其他单词关联起来

# Text Generation Transformer

# BERT

# GPT

#### What is input/output embedding
An embedding is a vector that **semantically** represents an object/input