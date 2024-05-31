项目在驱动云服务器进行训练，数据集为LibriSpeech，其他数据集直接删除了

需要设置的环境变量：export HYDRA_FULL_ERROR=1

训练模型运行代码：python main.py -cp conf -cn configs

原文🔗：https://github.com/tuanio/conformer-rnnt
