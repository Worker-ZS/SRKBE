
## Running SRKBE

```
CUDA_VISIBLE_DEVICES=0 python main.py --dataset FB-AUTO --num_iterations 200 --batch_size 64 --lr 0.005 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.2 --drop_ent 0.4 --eval_step 1 --valid_patience 10 -ary 2 -ary 4 -ary 5

CUDA_VISIBLE_DEVICES=1 python3 main.py --dataset JF17K-3 --num_iterations 100 --batch_size 64 --lr 0.005 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.2 --drop_ent 0.4 --eval_step 1 --valid_patience 10 -ary 3

CUDA_VISIBLE_DEVICES=2 python3 main.py --dataset JF17K-4 --num_iterations 100 --batch_size 64 --lr 0.005 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.2 --drop_ent 0.4 --eval_step 1 --valid_patience 10 -ary 4

CUDA_VISIBLE_DEVICES=3 python3 main.py --dataset JF17K --num_iterations 100 --batch_size 64 --lr 0.005 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.2 --drop_ent 0.4 --eval_step 1 --valid_patience 10 -ary 2 -ary 3 -ary 4 -ary 5 -ary 6

CUDA_VISIBLE_DEVICES=4 python3 main.py --dataset WikiPeople-4 --num_iterations 100 --batch_size 64 --lr 0.003 --dr 0.995 --K 10 --rdim 30 --m 2 --drop_role 0.0 --drop_ent 0.2 --eval_step 1 --valid_patience 10 -ary 4

CUDA_VISIBLE_DEVICES=4 python3 main.py --dataset WikiPeople --num_iterations 100 --batch_size 64 --lr 0.003 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.0 --drop_ent 0.2 --eval_step 1 --valid_patience 10 -ary 2 -ary 3 -ary 4 -ary 5 -ary 6 -ary 7 -ary 8 -ary 9

CUDA_VISIBLE_DEVICES=6 python3 main.py --dataset WN18 --num_iterations 100 --batch_size 64 --lr 0.003 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.0 --drop_ent 0.2 --eval_step 1 --valid_patience 10 -ary 2

CUDA_VISIBLE_DEVICES=7 python3 main.py --dataset FB15K --num_iterations 100 --batch_size 64 --lr 0.003 --dr 0.995 --K 10 --rdim 50 --m 2 --drop_role 0.0 --drop_ent 0.2 --eval_step 1 --valid_patience 10 -ary 2
```
