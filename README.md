# [](#header-1)[Project Overview](docs/index.md)

QianJiangYuan is an open source toolkit that allows AI scientists to spin up an AI cluster in turn-key fashion (either in a public cloud such as Aliyun/Azure, or in an on-perm cluster). It is derived from [DLWorkspace](https://github.com/microsoft/DLWorkspace), which has been used in daily production for Microsoft internal groups (e.g., Microsoft Cognitive Service, SwiftKey, Bing Relevance, etc...).
Once setup, the QianJiangYuan provides web UI and/or restful API that allows AI scientist to run job (interactive exploration, training, inferencing, data analystics)
on the cluster with resource allocated by cluster for each job (e.g., a single node job with a couple of GPUs with GPU Direct connection, or a distributed job with multiple GPUs per node). QianJiangYuan also provides
unified job template and operating environment that allows AI scientists to easily share their job and setting among themselves and with outside community. QianJiangYuan out-of-box supports all major deep learning toolkits (TensorFlow, CNTK, Caffe, MxNet, etc..), and supports popular big data analytic toolkit such as hadoop/spark. 

# [](#header-2)Tutorials

Here is a few short video clips that can quickly explain DLWorkspace. Note the PPT link will only work in github.com repo, not in github.com pages. 

* [QianJiangYuan: CNTK](https://youtu.be/3O0uwUwPRho) [(PPT)](docs/Presentation/Video/Running-CNTK.pptx)
* [QianJiangYuan: TensorFlow](https://youtu.be/Xa7exVurUmE) [(PPT)](docs/Presentation/Video/Running-TensorFlow.pptx)
* [QianJiangYuan: Spark](https://youtu.be/9kV9_w-eQYY) [(PPT)](docs/Presentation/Video/Running-Spark.pptx)
* [Installation-Azure](https://youtu.be/inDcl85-TRw) [(PPT)](docs/Presentation/Video/Installation-Azure.pptx)
* [Installation-On-Prem](https://youtu.be/T_00DrSxl70) [(PPT)](docs/Presentation/Video/Installation-On-Prem.pptx)

# [](#header-3)Documentations

## [Cluster Deployment](docs/deployment/Readme.md)

## [Frequently Asked Questions](docs/KnownIssues/Readme.md)

## [Presentation](docs/Presentation/1707/Readme.md)

# 中文文档
[初稿](https://qianjiangyuan.github.io/)