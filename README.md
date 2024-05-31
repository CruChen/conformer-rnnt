原文代码有BUG，已进行修改，并在驱动云服务器进行训练测试通过，使用的数据集为LibriSpeech。

后续会对conformer模型进行修改

需要设置的环境变量：export HYDRA_FULL_ERROR=1

训练模型运行代码：python main.py -cp conf -cn configs

原文🔗：https://github.com/tuanio/conformer-rnnt
