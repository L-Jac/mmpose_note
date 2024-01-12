# mmpos_note
[官方文档](https://mmpose.readthedocs.io/zh-cn/latest/installation.html)

## 挂代理
. ~/proxy.sh
```bash
HOST=127.0.0.1
PORT=7890
export http_proxy="http://$HOST:$PORT"
export https_proxy="http://$HOST:$PORT"
```
## Pytorch
[Pytorch](https://pytorch.org/)  
验证
```bash
python -c 'import torch;print(torch.__version__)'
```

## MMCV 建议找轮子
[MMCV安装文档](https://mmcv.readthedocs.io/en/latest/get_started/installation.html)

[MMCV轮子库](https://download.openmmlab.com/mmcv/dist/cu121/torch2.1/index.html)

示例
```bash
wget https://download.openmmlab.com/mmcv/dist/cu121/torch2.1.0/mmcv-2.1.0-cp311-cp311-manylinux1_x86_64.whl  
  
pip install mmcv-2.1.0-cp311-cp311-manylinux1_x86_64.whl 
```
