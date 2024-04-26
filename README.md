# YOLOV3

## Training Logs
```
Starting training for 300 epochs...

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
  0%|                                                                                                                                | 0/2 [00:00<?, ?it/s]C:\Users\Shubham\Documents\ERA\ERA Session 12\YoloV3\utils\utils.py:374: UserWarning: The torch.cuda.*DtypeTensor constructors are no longer recommended. It's best to use methods such as torch.tensor(data, dtype=*, device='cuda') to create tensors. (Triggered internally at ..\torch\csrc\tensor\python_tensor.cpp:80.)
  lcls, lbox, lobj = ft([0]), ft([0]), ft([0])
C:\Users\Shubham\anaconda3\envs\myenv\lib\site-packages\torch\cuda\memory.py:440: FutureWarning: torch.cuda.memory_cached has been renamed to torch.cuda.memory_reserved
  warnings.warn(
     0/299     8.09G      4.57       143         0       147        19       512: 100%|██████████████████████████████████████| 2/2 [00:05<00:00,  2.78s/it]
C:\Users\Shubham\anaconda3\envs\myenv\lib\site-packages\torch\functional.py:512: UserWarning: torch.meshgrid: in an upcoming release, it will be required to pass the indexing argument. (Triggered internally at ..\aten\src\ATen\native\TensorShape.cpp:3588.)
  return _VF.meshgrid(tensors, **kwargs)  # type: ignore[attr-defined]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:26<00:00, 13.39s/it]
                 all        20        21  0.000138         1   0.00285  0.000277

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     1/299     13.6G      4.64       124         0       129        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.24s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.94s/it]
                 all        20        21  0.000138         1   0.00285  0.000277

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     2/299     13.6G      4.67      79.5         0      84.2        15       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.30s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:26<00:00, 13.10s/it]
                 all        20        21  0.000712     0.905   0.00222   0.00142

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     3/299     7.33G      4.59      34.7         0      39.3        16       512: 100%|██████████████████████████████████████| 2/2 [00:07<00:00,  3.62s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.15s/it]
                 all        20        21  0.000712     0.905   0.00222   0.00142

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     4/299     7.33G       4.5      22.8         0      27.3        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.12s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.05s/it]
                 all        20        21         0         0   0.00127         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     5/299     7.33G       4.2      10.8         0        15        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.92s/it]
                 all        20        21         0         0   0.00127         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     6/299     7.33G      4.41      7.83         0      12.2        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.92s/it]
                 all        20        21         0         0   0.00129         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     7/299     7.93G      4.12      4.65         0      8.77        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:25<00:00, 12.62s/it]
                 all        20        21         0         0   0.00129         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     8/299     7.93G      4.47      3.72         0      8.19        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.62s/it]
                 all        20        21         0         0   0.00191         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     9/299     7.93G       3.9      3.48         0      7.37        26       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.12s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.75s/it]
                 all        20        21         0         0   0.00191         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    10/299     7.93G      4.22      2.75         0      6.97        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.21s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.49s/it]
                 all        20        21         0         0   0.00223         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    11/299     7.93G      3.69      2.96         0      6.66        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.15s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.54s/it]
                 all        20        21         0         0   0.00223         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    12/299     7.93G       4.2      2.82         0      7.02        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.18s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.45s/it]
                 all        20        21         0         0   0.00406         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    13/299     7.93G      3.32      2.68         0      6.01        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.17s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.21s/it]
                 all        20        21         0         0   0.00406         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    14/299     7.93G      3.52      2.85         0      6.37        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.20s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.52s/it]
                 all        20        21         0         0   0.00815         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    15/299     7.93G       3.5       2.5         0         6        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:26<00:00, 13.40s/it]
                 all        20        21         0         0   0.00815         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    16/299     7.93G      3.01      3.21         0      6.22        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:26<00:00, 13.35s/it]
                 all        20        21         0         0    0.0247         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    17/299     7.93G      2.89      3.15         0      6.04        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.09s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:27<00:00, 13.67s/it]
                 all        20        21         0         0    0.0247         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    18/299     7.93G      3.17      3.14         0      6.31        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.14s/it]
                 all        20        21         0         0    0.0737         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    19/299     7.93G      3.18      3.27         0      6.45        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.11s/it]
                 all        20        21         0         0    0.0737         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    20/299     7.93G      2.99      3.12         0      6.11        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.11s/it]
                 all        20        21         0         0     0.241         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    21/299     7.93G      2.76      3.72         0      6.49        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.04s/it]
                 all        20        21         0         0     0.241         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    22/299     7.93G      2.97      3.45         0      6.42        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.96s/it]
                 all        20        21         0         0      0.37         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    23/299     7.93G      2.63      3.11         0      5.74        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.09s/it]
                 all        20        21         0         0      0.37         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    24/299     7.93G         3      3.11         0      6.11        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.13s/it]
                 all        20        21         0         0     0.495         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    25/299     7.93G      2.67      2.93         0       5.6        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.57s/it]
                 all        20        21         0         0     0.495         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    26/299     7.93G      2.41      3.59         0         6        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.09s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:26<00:00, 13.09s/it]
                 all        20        21         1    0.0476     0.678    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    27/299     7.93G       2.1      3.02         0      5.12        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.10s/it]
                 all        20        21         1    0.0476     0.678    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    28/299     7.93G      2.38      2.83         0       5.2        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.98s/it]
                 all        20        21         1    0.0476      0.85    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    29/299     7.93G      2.63      3.12         0      5.75        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.06s/it]
                 all        20        21         1    0.0476      0.85    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    30/299     7.93G      2.64      2.67         0       5.3        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.01s/it]
                 all        20        21         1    0.0476     0.839    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    31/299     7.93G      2.62      2.93         0      5.55        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.03s/it]
                 all        20        21         1    0.0476     0.839    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    32/299     7.93G      2.46      2.76         0      5.22        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.04s/it]
                 all        20        21         1    0.0476     0.942    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    33/299     7.93G      2.42       3.1         0      5.51        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.90s/it]
                 all        20        21         1    0.0476     0.942    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    34/299     7.93G      2.14      2.23         0      4.38        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 11.00s/it]
                 all        20        21         1    0.0476     0.939    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    35/299     7.93G      2.48      2.41         0      4.89        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.91s/it]
                 all        20        21         1    0.0476     0.939    0.0909

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    36/299     7.93G       2.4      2.63         0      5.03        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.93s/it]
                 all        20        21     0.551    0.0622     0.904     0.112

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    37/299     7.93G      2.59      2.16         0      4.75        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.78s/it]
                 all        20        21     0.551    0.0622     0.904     0.112

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    38/299     7.93G      2.78      2.37         0      5.15        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.77s/it]
                 all        20        21         1     0.511      0.95     0.677

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    39/299     7.93G      2.86      1.79         0      4.65        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.83s/it]
                 all        20        21         1     0.511      0.95     0.677

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    40/299     7.93G       2.6      2.44         0      5.05        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.76s/it]
                 all        20        21      0.78     0.844     0.873     0.811

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    41/299     7.93G       2.6      2.19         0      4.78        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.88s/it]
                 all        20        21      0.78     0.844     0.873     0.811

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    42/299     7.93G      2.43       2.2         0      4.62        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.78s/it]
                 all        20        21     0.683         1     0.868     0.811

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    43/299     7.93G      2.51      1.79         0       4.3        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.11s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.77s/it]
                 all        20        21     0.683         1     0.868     0.811

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    44/299     7.93G      2.33      1.75         0      4.09        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.77s/it]
                 all        20        21     0.338         1     0.676     0.506

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    45/299     7.93G      2.54      1.56         0      4.11        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.81s/it]
                 all        20        21     0.338         1     0.676     0.506

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    46/299     7.93G      2.78       1.8         0      4.58        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.75s/it]
                 all        20        21     0.392         1     0.825     0.563

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    47/299     7.93G       3.1      1.32         0      4.41        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.77s/it]
                 all        20        21     0.392         1     0.825     0.563

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    48/299     7.93G      2.61      1.14         0      3.75        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.78s/it]
                 all        20        21     0.239     0.952     0.842     0.382

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    49/299     7.93G      2.17     0.928         0       3.1        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.86s/it]
                 all        20        21     0.239     0.952     0.842     0.382

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    50/299     7.93G      2.69     0.971         0      3.66        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.82s/it]
                 all        20        21     0.375         1      0.91     0.545

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    51/299     7.93G      3.26      1.33         0      4.59        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.15s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.73s/it]
                 all        20        21     0.375         1      0.91     0.545

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    52/299     7.93G      2.95      1.12         0      4.07        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.66s/it]
                 all        20        21      0.29         1      0.84      0.45

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    53/299     7.93G      2.77      1.08         0      3.84        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.09s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.68s/it]
                 all        20        21      0.29         1      0.84      0.45

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    54/299     7.93G      2.57      1.23         0       3.8        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.86s/it]
                 all        20        21      0.34         1     0.886     0.507

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    55/299     7.93G      2.28     0.842         0      3.13        26       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.82s/it]
                 all        20        21      0.34         1     0.886     0.507

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    56/299     7.93G      2.91      0.95         0      3.86        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.16s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.83s/it]
                 all        20        21     0.262     0.952     0.723     0.411

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    57/299     7.93G      3.06     0.861         0      3.92        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.79s/it]
                 all        20        21     0.262     0.952     0.723     0.411

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    58/299     7.93G      2.53     0.881         0      3.41        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.12s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.77s/it]
                 all        20        21     0.641         1     0.852     0.781

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    59/299     7.93G      2.32     0.871         0      3.19        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.91s/it]
                 all        20        21     0.641         1     0.852     0.781

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    60/299     7.93G      2.53      1.04         0      3.57        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.82s/it]
                 all        20        21     0.387         1      0.66     0.558

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    61/299     7.93G      3.19     0.736         0      3.93        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.79s/it]
                 all        20        21     0.387         1      0.66     0.558

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    62/299     7.93G      2.65      0.92         0      3.57        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.71s/it]
                 all        20        21     0.618         1     0.754     0.764

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    63/299     7.93G      1.75     0.768         0      2.52        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.00s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.85s/it]
                 all        20        21     0.618         1     0.754     0.764

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    64/299     7.93G      2.12     0.953         0      3.07        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.12s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.74s/it]
                 all        20        21     0.686     0.857     0.748     0.762

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    65/299     7.93G      2.76     0.885         0      3.65        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.71s/it]
                 all        20        21     0.686     0.857     0.748     0.762

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    66/299     7.93G      2.22     0.826         0      3.05        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.12s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.70s/it]
                 all        20        21      0.48     0.905     0.692     0.627

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    67/299     7.93G      2.02     0.729         0      2.74        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.71s/it]
                 all        20        21      0.48     0.905     0.692     0.627

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    68/299     7.93G      2.62     0.675         0      3.29        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.15s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.77s/it]
                 all        20        21     0.505     0.905      0.75     0.648

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    69/299     7.93G       3.2     0.702         0      3.91        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.70s/it]
                 all        20        21     0.505     0.905      0.75     0.648

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    70/299     7.93G      2.68      0.86         0      3.54        26       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.84s/it]
                 all        20        21     0.485      0.94     0.727      0.64

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    71/299     7.93G      1.97     0.769         0      2.74        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:24<00:00, 12.35s/it]
                 all        20        21     0.485      0.94     0.727      0.64

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    72/299     7.93G      2.06     0.708         0      2.76        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.72s/it]
                 all        20        21     0.803     0.905     0.941     0.851

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    73/299     7.93G      2.07     0.647         0      2.71        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.65s/it]
                 all        20        21     0.803     0.905     0.941     0.851

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    74/299     7.93G      1.99     0.671         0      2.66        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.69s/it]
                 all        20        21     0.531     0.972     0.755     0.687

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    75/299     7.93G      2.12     0.835         0      2.95        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.16s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.66s/it]
                 all        20        21     0.531     0.972     0.755     0.687

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    76/299     7.93G      2.37      0.78         0      3.15        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.73s/it]
                 all        20        21     0.182     0.952     0.727     0.306

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    77/299     7.93G      2.59      0.61         0       3.2        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.182     0.952     0.727     0.306

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    78/299     7.93G      2.37      0.74         0      3.11        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.73s/it]
                 all        20        21     0.219     0.952     0.805     0.357

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    79/299     7.93G         2     0.482         0      2.48        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.57s/it]
                 all        20        21     0.219     0.952     0.805     0.357

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    80/299     7.93G      2.09     0.896         0      2.99        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.66s/it]
                 all        20        21      0.16     0.952     0.769     0.273

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    81/299     7.93G      2.24     0.714         0      2.95        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21      0.16     0.952     0.769     0.273

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    82/299     7.93G      1.97       0.9         0      2.87        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.60s/it]
                 all        20        21     0.803     0.952     0.939     0.872

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    83/299     7.93G      1.95     0.642         0      2.59        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.64s/it]
                 all        20        21     0.803     0.952     0.939     0.872

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    84/299     7.93G       2.1      0.59         0      2.69        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.66s/it]
                 all        20        21     0.806     0.952     0.955     0.873

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    85/299     7.93G      2.35     0.594         0      2.94        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.806     0.952     0.955     0.873

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    86/299     7.93G      2.21     0.766         0      2.98        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.70s/it]
                 all        20        21     0.862     0.952      0.97     0.905

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    87/299     7.93G      1.91     0.729         0      2.64        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21     0.862     0.952      0.97     0.905

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    88/299     7.93G      2.19     0.625         0      2.82        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.57s/it]
                 all        20        21         1     0.952      0.99     0.975

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    89/299     7.93G      2.26     0.684         0      2.94        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.63s/it]
                 all        20        21         1     0.952      0.99     0.975

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    90/299     7.93G      2.12     0.834         0      2.96        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.63s/it]
                 all        20        21     0.864     0.952     0.969     0.906

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    91/299     7.93G      1.99     0.669         0      2.65        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.65s/it]
                 all        20        21     0.864     0.952     0.969     0.906

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    92/299     7.93G      1.85     0.501         0      2.35        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.63s/it]
                 all        20        21         1     0.896      0.99     0.945

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    93/299     7.93G       1.7     0.646         0      2.35        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.76s/it]
                 all        20        21         1     0.896      0.99     0.945

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    94/299     7.93G      1.93     0.593         0      2.52        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.72s/it]
                 all        20        21     0.899     0.851     0.975     0.874

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    95/299     7.93G      1.85     0.567         0      2.42        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.18s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.64s/it]
                 all        20        21     0.899     0.851     0.975     0.874

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    96/299     7.93G      2.04     0.632         0      2.67        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21      0.95     0.909     0.971     0.929

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    97/299     7.93G      2.32     0.668         0      2.99        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.57s/it]
                 all        20        21      0.95     0.909     0.971     0.929

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    98/299     7.93G      1.98     0.557         0      2.54        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.64s/it]
                 all        20        21     0.902      0.88     0.964     0.891

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
    99/299     7.93G      1.78     0.608         0      2.39        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21     0.902      0.88     0.964     0.891

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   100/299     7.93G      2.16      0.57         0      2.73        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.48s/it]
                 all        20        21     0.985     0.905     0.989     0.943

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   101/299     7.93G      2.74     0.497         0      3.24        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.61s/it]
                 all        20        21     0.985     0.905     0.989     0.943

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   102/299     7.93G      2.29     0.559         0      2.85        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.64s/it]
                 all        20        21      0.95     0.903     0.982     0.926

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   103/299     7.93G      2.13     0.543         0      2.67        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21      0.95     0.903     0.982     0.926

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   104/299     7.93G      1.78      0.69         0      2.47        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.61s/it]
                 all        20        21     0.961     0.905     0.987     0.932

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   105/299     7.93G       1.7     0.533         0      2.23        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.961     0.905     0.987     0.932

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   106/299     7.93G      1.87     0.598         0      2.46        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.57s/it]
                 all        20        21     0.865     0.913     0.955     0.888

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   107/299     7.93G         2     0.541         0      2.54        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.61s/it]
                 all        20        21     0.865     0.913     0.955     0.888

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   108/299     7.93G      2.04     0.511         0      2.55        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21     0.717     0.905     0.922       0.8

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   109/299     7.93G      2.19     0.552         0      2.74        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.717     0.905     0.922       0.8

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   110/299     7.93G      1.83     0.596         0      2.42        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.618     0.905     0.733     0.734

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   111/299     7.93G      1.58     0.596         0      2.18        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21     0.618     0.905     0.733     0.734

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   112/299     7.93G      1.79     0.683         0      2.48        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21     0.556     0.894     0.556     0.685

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   113/299     7.93G      1.72     0.637         0      2.35        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.556     0.894     0.556     0.685

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   114/299     7.93G      1.78     0.528         0      2.31        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.55s/it]
                 all        20        21     0.486     0.905     0.523     0.632

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   115/299     7.93G      1.92     0.546         0      2.47        20       512: 100%|██████████████████████████████████████| 2/2 [00:01<00:00,  1.00it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.486     0.905     0.523     0.632

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   116/299     7.93G      1.77     0.496         0      2.27        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.09s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21     0.525     0.905     0.538     0.664

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   117/299     7.93G      1.74     0.622         0      2.36        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.53s/it]
                 all        20        21     0.525     0.905     0.538     0.664

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   118/299     7.93G      1.72     0.646         0      2.36        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21     0.518     0.905     0.542     0.658

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   119/299     7.93G      1.65     0.454         0       2.1        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.64s/it]
                 all        20        21     0.518     0.905     0.542     0.658

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   120/299     7.93G      1.61     0.572         0      2.18        27       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.439     0.905      0.49     0.591

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   121/299     7.93G      1.83     0.583         0      2.41        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.439     0.905      0.49     0.591

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   122/299     7.93G       1.8      0.51         0      2.31        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.60s/it]
                 all        20        21     0.476     0.905     0.493     0.624

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   123/299     7.93G      1.89     0.427         0      2.32        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.476     0.905     0.493     0.624

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   124/299     7.93G      1.84     0.678         0      2.51        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21     0.412     0.905     0.418     0.566

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   125/299     7.93G      2.05     0.573         0      2.62        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.61s/it]
                 all        20        21     0.412     0.905     0.418     0.566

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   126/299     7.93G      2.08     0.474         0      2.55        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.46s/it]
                 all        20        21     0.403     0.905     0.406     0.558

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   127/299     7.93G      1.73      0.55         0      2.28        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.63s/it]
                 all        20        21     0.403     0.905     0.406     0.558

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   128/299     7.93G      1.58     0.601         0      2.18        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.12s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.48s/it]
                 all        20        21     0.427     0.905     0.441     0.581

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   129/299     7.93G      1.77     0.603         0      2.37        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21     0.427     0.905     0.441     0.581

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   130/299     7.93G      1.72      0.43         0      2.15        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21      0.59     0.961     0.597     0.732

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   131/299     7.93G      1.63     0.582         0      2.21        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.52s/it]
                 all        20        21      0.59     0.961     0.597     0.732

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   132/299     7.93G      1.61     0.588         0       2.2        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21     0.633     0.985     0.642      0.77

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   133/299     7.93G      1.69     0.615         0       2.3        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21     0.633     0.985     0.642      0.77

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   134/299     7.93G      1.62     0.551         0      2.17        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.581     0.991     0.585     0.733

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   135/299     7.93G      1.74     0.577         0      2.32        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.65s/it]
                 all        20        21     0.581     0.991     0.585     0.733

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   136/299     7.93G       1.6     0.514         0      2.11        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.541     0.952     0.571      0.69

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   137/299     7.93G      2.12     0.563         0      2.68        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.60s/it]
                 all        20        21     0.541     0.952     0.571      0.69

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   138/299     7.93G      1.62     0.473         0      2.09        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21     0.534     0.983      0.54     0.692

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   139/299     7.93G      1.64     0.383         0      2.02        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.534     0.983      0.54     0.692

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   140/299     7.93G      1.67     0.725         0      2.39        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.46s/it]
                 all        20        21         1     0.975     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   141/299     7.93G      1.77     0.435         0       2.2        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21         1     0.975     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   142/299     7.93G      1.72     0.606         0      2.33        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.48s/it]
                 all        20        21         1     0.961     0.995      0.98

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   143/299     7.93G      1.74     0.431         0      2.17        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.45s/it]
                 all        20        21         1     0.961     0.995      0.98

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   144/299     7.93G      1.77     0.582         0      2.35        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21         1      0.92     0.995     0.958

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   145/299     7.93G      1.59     0.528         0      2.12        19       512: 100%|██████████████████████████████████████| 2/2 [00:01<00:00,  1.00it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.63s/it]
                 all        20        21         1      0.92     0.995     0.958

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   146/299     7.93G      1.57     0.554         0      2.12        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.55s/it]
                 all        20        21         1      0.93     0.995     0.964

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   147/299     7.93G      1.61     0.619         0      2.23        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.50s/it]
                 all        20        21         1      0.93     0.995     0.964

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   148/299     7.93G      1.59     0.464         0      2.06        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21         1     0.942     0.995      0.97

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   149/299     7.93G      1.67     0.534         0      2.21        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.48s/it]
                 all        20        21         1     0.942     0.995      0.97

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   150/299     7.93G      1.51     0.658         0      2.16        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21         1     0.943     0.995     0.971

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   151/299     7.93G      1.42      0.47         0      1.89        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21         1     0.943     0.995     0.971

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   152/299     7.93G      1.63     0.529         0      2.16        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21         1     0.958     0.995     0.978

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   153/299     7.93G      1.65     0.596         0      2.24        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.65s/it]
                 all        20        21         1     0.958     0.995     0.978

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   154/299     7.93G      1.44     0.558         0      1.99        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.60s/it]
                 all        20        21         1     0.877     0.945     0.934

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   155/299     7.93G      1.21      0.52         0      1.73        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.50s/it]
                 all        20        21         1     0.877     0.945     0.934

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   156/299     7.93G      1.53     0.568         0       2.1        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.09s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.46s/it]
                 all        20        21         1     0.884     0.925     0.939

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   157/299     7.93G      1.54     0.517         0      2.06        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.61s/it]
                 all        20        21         1     0.884     0.925     0.939

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   158/299     7.93G      1.59     0.438         0      2.03        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21         1      0.89     0.914     0.942

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   159/299     7.93G      1.59     0.512         0       2.1        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21         1      0.89     0.914     0.942

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   160/299     7.93G      1.62     0.511         0      2.13        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.53s/it]
                 all        20        21         1     0.889     0.929     0.941

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   161/299     7.93G      1.53     0.493         0      2.03        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.52s/it]
                 all        20        21         1     0.889     0.929     0.941

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   162/299     7.93G      1.54      0.48         0      2.02        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21         1     0.884     0.942     0.938

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   163/299     7.93G      1.37     0.317         0      1.68        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.13s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.42s/it]
                 all        20        21         1     0.884     0.942     0.938

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   164/299     7.93G      1.42     0.452         0      1.87        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21         1     0.896     0.936     0.945

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   165/299     7.93G      1.59     0.627         0      2.22        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21         1     0.896     0.936     0.945

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   166/299     7.93G      1.51     0.605         0      2.11        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.07s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.69s/it]
                 all        20        21         1     0.892     0.958     0.943

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   167/299     7.93G      1.44     0.483         0      1.92        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21         1     0.892     0.958     0.943

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   168/299     7.93G      1.38      0.51         0      1.89        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.897     0.905     0.944     0.901

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   169/299     7.93G      1.53     0.434         0      1.96        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.63s/it]
                 all        20        21     0.897     0.905     0.944     0.901

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   170/299     7.93G      1.34     0.394         0      1.73        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.926     0.905     0.972     0.915

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   171/299     7.93G      1.56     0.481         0      2.04        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.48s/it]
                 all        20        21     0.926     0.905     0.972     0.915

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   172/299     7.93G      1.49     0.478         0      1.97        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.55s/it]
                 all        20        21     0.908     0.944     0.971     0.926

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   173/299     7.93G       1.8     0.561         0      2.36        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.908     0.944     0.971     0.926

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   174/299     7.93G      1.36     0.413         0      1.78        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.816     0.952     0.957     0.879

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   175/299     7.93G       1.3     0.469         0      1.77        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.02s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.59s/it]
                 all        20        21     0.816     0.952     0.957     0.879

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   176/299     7.93G      1.25     0.364         0      1.62        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.71s/it]
                 all        20        21     0.743         1     0.953     0.853

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   177/299     7.93G      1.23     0.474         0       1.7        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.61s/it]
                 all        20        21     0.743         1     0.953     0.853

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   178/299     7.93G       1.4     0.451         0      1.85        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.11s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.64s/it]
                 all        20        21     0.827         1     0.989     0.905

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   179/299     7.93G      1.45     0.489         0      1.94        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.00s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.87s/it]
                 all        20        21     0.827         1     0.989     0.905

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   180/299     7.93G      1.46     0.648         0      2.11        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.737         1     0.967     0.849

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   181/299     7.93G      1.21     0.545         0      1.76        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.01s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.737         1     0.967     0.849

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   182/299     7.93G      1.22      0.51         0      1.73        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.11s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21     0.722         1     0.973     0.839

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   183/299     7.93G      1.07     0.439         0      1.51        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.10s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21     0.722         1     0.973     0.839

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   184/299     7.93G      1.16     0.284         0      1.44        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.55s/it]
                 all        20        21     0.718         1     0.971     0.836

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   185/299     7.93G      1.23     0.474         0       1.7        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.11s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.58s/it]
                 all        20        21     0.718         1     0.971     0.836

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   186/299     7.93G      1.14     0.434         0      1.57        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.08s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.62s/it]
                 all        20        21     0.676         1     0.957     0.807

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   187/299     7.93G      1.33     0.497         0      1.83        23       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.03s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.49s/it]
                 all        20        21     0.676         1     0.957     0.807

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   188/299     7.93G      1.22     0.486         0       1.7        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.04s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.711         1     0.974     0.831

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   189/299     7.93G      1.19     0.323         0      1.51        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:20<00:00, 10.47s/it]
                 all        20        21     0.711         1     0.974     0.831

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   190/299     7.93G      1.25     0.477         0      1.72        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.09s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.55s/it]
                 all        20        21     0.809         1     0.989     0.895

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   191/299     7.93G      1.35     0.518         0      1.87        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.05s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.56s/it]
                 all        20        21     0.809         1     0.989     0.895

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   192/299     7.93G      1.22     0.545         0      1.77        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.06s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:21<00:00, 10.51s/it]
                 all        20        21     0.836         1     0.992     0.911

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   193/299     7.93G      1.24     0.365         0      1.61        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.30s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.87s/it]
                 all        20        21     0.836         1     0.992     0.911

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   194/299     7.93G      1.22     0.616         0      1.83        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.38s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.79s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   195/299     7.93G      1.26     0.392         0      1.65        20       512: 100%|██████████████████████████████████████| 2/2 [00:03<00:00,  1.52s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:24<00:00, 12.05s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   196/299     7.93G      1.13     0.448         0      1.58        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.45s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:25<00:00, 12.66s/it]
                 all        20        21     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   197/299     7.93G      1.23     0.456         0      1.68        21       512: 100%|██████████████████████████████████████| 2/2 [00:03<00:00,  1.51s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.86s/it]
                 all        20        21     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   198/299     7.93G      1.18     0.489         0      1.67        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.30s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.12s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   199/299     7.93G      1.12     0.406         0      1.53        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.28s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.07s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   200/299     7.93G      1.21      0.59         0       1.8        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.28s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.02s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   201/299     7.93G         1     0.413         0      1.41        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.32s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.12s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   202/299     7.93G      1.12     0.401         0      1.52        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.29s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.30s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   203/299     7.93G      1.07     0.398         0      1.47        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.30s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:31<00:00, 15.64s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   204/299     7.93G      1.15     0.554         0       1.7        27       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.32s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.34s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   205/299     7.93G       1.1     0.281         0      1.38        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.27s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.15s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   206/299     7.93G      1.18     0.414         0       1.6        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.30s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.20s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   207/299     7.93G      1.16     0.469         0      1.63        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.34s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.29s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   208/299     7.93G      1.21      0.43         0      1.64        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.29s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.28s/it]
                 all        20        21     0.969         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   209/299     7.93G      1.19     0.434         0      1.62        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.36s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.45s/it]
                 all        20        21     0.969         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   210/299     7.93G      1.13     0.495         0      1.63        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.33s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.63s/it]
                 all        20        21     0.968         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   211/299     7.93G      1.15     0.518         0      1.67        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.26s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.35s/it]
                 all        20        21     0.968         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   212/299     7.93G     0.984     0.403         0      1.39        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.28s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.33s/it]
                 all        20        21     0.968         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   213/299     7.93G     0.974     0.439         0      1.41        22       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.22s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.39s/it]
                 all        20        21     0.968         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   214/299     7.93G      1.09     0.411         0       1.5        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.28s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.20s/it]
                 all        20        21     0.969         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   215/299     7.93G      1.03     0.409         0      1.44        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.34s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.28s/it]
                 all        20        21     0.969         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   216/299     7.93G      1.11     0.357         0      1.46        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.33s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.48s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   217/299     7.93G      1.07     0.437         0      1.51        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.28s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.15s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   218/299     7.93G      1.06     0.356         0      1.42        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.34s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.34s/it]
                 all        20        21     0.973         1     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   219/299     7.93G      1.01     0.415         0      1.43        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.40s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.35s/it]
                 all        20        21     0.973         1     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   220/299     7.93G     0.927      0.37         0       1.3        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.34s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.30s/it]
                 all        20        21     0.976         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   221/299     7.93G     0.998     0.458         0      1.46        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.34s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.83s/it]
                 all        20        21     0.976         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   222/299     7.93G      1.04     0.464         0       1.5        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.39s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.47s/it]
                 all        20        21     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   223/299     7.93G      1.19     0.384         0      1.57        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.35s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.46s/it]
                 all        20        21     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   224/299     7.93G      1.21     0.501         0      1.71        20       512: 100%|██████████████████████████████████████| 2/2 [00:03<00:00,  1.64s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.49s/it]
                 all        20        21     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   225/299     7.93G      1.11      0.37         0      1.48        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.27s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.59s/it]
                 all        20        21     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   226/299     7.93G      1.15     0.465         0      1.62        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.35s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.49s/it]
                 all        20        21     0.975         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   227/299     7.93G      1.07     0.423         0      1.49        26       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.27s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.65s/it]
                 all        20        21     0.975         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   228/299     7.93G      1.13     0.408         0      1.54        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.40s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.61s/it]
                 all        20        21     0.975         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   229/299     7.93G     0.982     0.448         0      1.43        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.37s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.26s/it]
                 all        20        21     0.975         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   230/299     7.93G      1.02     0.344         0      1.36        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.39s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:24<00:00, 12.37s/it]
                 all        20        21     0.976         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   231/299     7.93G      1.12     0.352         0      1.47        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.42s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:22<00:00, 11.38s/it]
                 all        20        21     0.976         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   232/299     7.93G      1.04     0.361         0       1.4        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.33s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:31<00:00, 15.51s/it]
                 all        20        21     0.978         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   233/299     7.93G     0.898      0.35         0      1.25        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.25s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.49s/it]
                 all        20        21     0.978         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   234/299     7.93G         1     0.371         0      1.37        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.32s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.50s/it]
                 all        20        21     0.982         1     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   235/299     7.93G      1.11       0.4         0      1.51        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.28s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.48s/it]
                 all        20        21     0.982         1     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   236/299     7.93G     0.977     0.554         0      1.53        25       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.38s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:26<00:00, 13.28s/it]
                 all        20        21     0.979         1     0.995      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   237/299     7.93G     0.932      0.34         0      1.27        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.46s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.71s/it]
                 all        20        21     0.979         1     0.995      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   238/299     7.93G     0.966     0.396         0      1.36        21       512: 100%|██████████████████████████████████████| 2/2 [00:03<00:00,  1.65s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:23<00:00, 11.64s/it]
                 all        20        21     0.977         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   239/299     7.93G     0.882     0.269         0      1.15        19       512: 100%|██████████████████████████████████████| 2/2 [00:03<00:00,  1.52s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.27s/it]
                 all        20        21     0.977         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   240/299     7.93G         1     0.431         0      1.43        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.45s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.29s/it]
                 all        20        21     0.975         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   241/299     7.93G     0.988     0.458         0      1.45        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.26s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.41s/it]
                 all        20        21     0.975         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   242/299     7.93G     0.864     0.251         0      1.12        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.34s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:31<00:00, 15.61s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   243/299     7.93G     0.837     0.315         0      1.15        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.42s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.22s/it]
                 all        20        21     0.974         1     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   244/299     7.93G     0.911     0.311         0      1.22        24       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.48s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.33s/it]
                 all        20        21     0.972         1     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   245/299     7.93G     0.783     0.347         0      1.13        21       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.38s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.42s/it]
                 all        20        21     0.972         1     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   246/299     7.93G     0.842     0.419         0      1.26        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.27s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.28s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   247/299     7.93G     0.916     0.374         0      1.29        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.31s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.34s/it]
                 all        20        21     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   248/299     7.93G      0.73     0.359         0      1.09        20       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.41s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.43s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   249/299     7.93G     0.898     0.486         0      1.38        18       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.21s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.23s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
  0%|                                                                                                                                | 0/2 [00:00<?, ?it/s]
Model Bias Summary:    layer        regression        objectness    classification
                          89      -0.08+/-0.27      -9.69+/-2.35       0.02+/-0.01
                         101       0.19+/-0.24     -10.25+/-0.95       0.04+/-0.00
                         113       0.01+/-0.04      -9.09+/-1.61      -0.00+/-0.01
   250/299     7.93G     0.884     0.289         0      1.17        17       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.46s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.42s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   251/299     7.93G     0.859     0.307         0      1.17        16       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.35s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:30<00:00, 15.35s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   252/299     7.93G     0.832     0.353         0      1.19        23       512: 100%|██████████████████████████████████████| 2/2 [00:03<00:00,  1.61s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:29<00:00, 14.61s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   253/299     7.93G     0.896     0.322         0      1.22        19       512: 100%|██████████████████████████████████████| 2/2 [00:02<00:00,  1.24s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1:   0%|                                                       Class    Images   Targets         P         R   mAP@0.5        F1:  50%|███████████████████                   |                Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████|                Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████████████████████████████████| 2/2 [00:28<00:00, 14.27s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   254/299     7.93G     0.896     0.269         0      1.17        20       512: 100%|█████████| 2/2 [00:02<00:00,  1.30s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|█████████| 2/2 [00:28<00:00, 14.00s/it]
                 all        20        21      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
   255/299     7.93G     0.913     0.311         0      1.22        18       512: 100%|█████████| 2/2 [00:02<00:00,  1.23s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1:   0%|                 | 0/2 [00:00<?, ?it/s]
```
## Training Curves

## Classified Images
