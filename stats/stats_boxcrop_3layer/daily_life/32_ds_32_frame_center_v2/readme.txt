Dataset: /home/Dataset/aggregorio_videos_pytorch_centercrop/daily_life/train
Classes: ['A13', 'A14', 'A15', 'A16', 'A17', 'A18', 'A19']
Classes to index:
Label: A13 index: 0
Label: A14 index: 1
Label: A15 index: 2
Label: A16 index: 3
Label: A17 index: 4
Label: A18 index: 5
Label: A19 index: 6
Numero di frame: 32
Downsample: 2
Balance: True
Padding: False
removed: 1
Temporal annotation: None
Numero Azioni 343
A13 	 49
A14 	 49
A15 	 49
A16 	 49
A17 	 49
A18 	 49
A19 	 49
Dataset: /home/Dataset/aggregorio_videos_pytorch_centercrop/daily_life/test
Classes: ['A13', 'A14', 'A15', 'A16', 'A17', 'A18', 'A19']
Classes to index:
Label: A13 index: 0
Label: A14 index: 1
Label: A15 index: 2
Label: A16 index: 3
Label: A17 index: 4
Label: A18 index: 5
Label: A19 index: 6
Numero di frame: 32
Downsample: 2
Balance: False
Padding: False
removed: 0
Temporal annotation: None
Numero Azioni 130
A13 	 20
A14 	 20
A15 	 20
A16 	 20
A17 	 20
A18 	 20
A19 	 10
['mixed_5c.branch_0.conv3d.weight', 'mixed_5c.branch_0.batch3d.weight', 'mixed_5c.branch_0.batch3d.bias', 'mixed_5c.branch_1.0.conv3d.weight', 'mixed_5c.branch_1.0.batch3d.weight', 'mixed_5c.branch_1.0.batch3d.bias', 'mixed_5c.branch_1.1.conv3d.weight', 'mixed_5c.branch_1.1.batch3d.weight', 'mixed_5c.branch_1.1.batch3d.bias', 'mixed_5c.branch_2.0.conv3d.weight', 'mixed_5c.branch_2.0.batch3d.weight', 'mixed_5c.branch_2.0.batch3d.bias', 'mixed_5c.branch_2.1.conv3d.weight', 'mixed_5c.branch_2.1.batch3d.weight', 'mixed_5c.branch_2.1.batch3d.bias', 'mixed_5c.branch_3.1.conv3d.weight', 'mixed_5c.branch_3.1.batch3d.weight', 'mixed_5c.branch_3.1.batch3d.bias', 'conv3d_0c_1x1.conv3d.weight', 'conv3d_0c_1x1.conv3d.bias']
batch size: 32
numero epoche: 50
best model at epoch: 12
drop out prob: 0.0
SGD (
Parameter Group 0
    dampening: 0
    initial_lr: 0.1
    lr: 0.0010000000000000002
    momentum: 0.9
    nesterov: False
    weight_decay: 0.001
)
CrossEntropyLoss()
{'milestones': [15, 40], 'gamma': 0.1, 'base_lrs': [0.1], 'last_epoch': 49}
