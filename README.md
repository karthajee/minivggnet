# minivggnet
An implementation of a MiniVGGNet:

[1] 2 blocks of CONV => ACT => BN => CONV => ACT => BN connected via POOL => DROPOUT
[2] 3x3 filters throughout
[3] FC layers connected by DROPOUT) in tensorflow.keras
[4] Momentum & Nesterov Acceleration turned on for stability
[5] Step Decay with a Drop Factor=0.5 implemented to slash learning rates every 5 epochs
