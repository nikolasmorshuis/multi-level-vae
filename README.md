# multi-level-vae

This is a fork of a repository that can be found here https://github.com/ananyahjha93/multi-level-vae

In the branch 'efficient' I applied some changes in the utils.py file, to make operations such as 'accumulate_group_evidence' and 'group_wise_reparametrize' more efficient, by replacing for-loops with vectorized operations.

Every training epoch of the implemented example now takes 6 times less time compared to the original program. 
