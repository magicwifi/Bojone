# 苏神http://kexue.fm 学习总结

#### nlp轮子
* crf:crf:crf_keras
* viterbi:crf:word_seg
* attention:attention:attention_keras
* to_mask:attention:attention_keras
* reuse::attention:attention_keras
* beam_search:seq2seq:seq2seq
* OurBidirectional:seq2seq:seq2seq
* Embedding与词向量:https://kexue.fm/archives/4122

#### nlp应用
* cnn+crf:crf:word_seg
* bilstm:crf:bilstm_fenci
* 分词:样本构建:https://kexue.fm/archives/4245
* 摘要:seq2seq:seq2seq

#### Keras Trick
* Keras中自定义复杂的loss函数 https://kexue.fm/archives/4493
* mask mask = Lambda(lambda x: K.cast(K.greater(K.expand_dims(x, 2), 0), 'float32'))(x) https://kexue.fm/archives/6810
* Keras 训练阶段给输入加入一些噪声，而测试阶段则去掉 https://kexue.fm/archives/5765
* Keras 超参数修改，而测试阶段则去掉 https://kexue.fm/archives/5765
* 支持在各阶段定义回调函数 https://kexue.fm/archives/5765
* 分层的学习率和梯度裁剪（梯度裁剪的作用） https://kexue.fm/archives/6418
* 权重滑动平均  https://kexue.fm/archives/6575
* 层复用 结构复用和权值共享 https://kexue.fm/archives/6985
* 软batch https://kexue.fm/archives/6794
