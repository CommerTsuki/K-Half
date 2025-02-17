# K-Half
Requirment:

torch==11.3<br>
transformers<br>
numpy<br>
Scikiit-learn<br>
matplotlib<br>
tqdm

python label.py —dataset []
 
python out.py —dataset [] —train_file [train, test, valid]  —threshold [validity threshold]

python train.py --dataset [] --train_file  [train, test, valid] --entity_out_dim_1 [] --entity_out_dim_[] --epochs [] --batch [] --threshold []

For example:

python label.py —dataset ICEWS14

python out.py —dataset ICEWS14 —train_file train —threshold 0.01


python train.py --dataset ICEWS14 --train_file train --entity_out_dim_1 32 --entity_out_dim_2 32 --epochs 50 --batch 5000 --threshold 0

cd data

Transfer the dataset to the model you want to run.
