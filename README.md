# scalc

scalc is a script that handles various Slurm calculations that can be handy.

## Usage

Simply run scalc and it will give you a menu of options of things it can calculate.  Then follow the instructions.  Currently this code can calcuate:

1. The projected new fairshare score for an account based on a given RawShare score and the account's current usage.
2. The RawShares that would be necessary to acheive a given fairshare score assuming the account's current usage is constant.
3. The estimated time it will take for the fairshare score to reach a current level assuming no new jobs.  This is currently set to use 28 days as the halflife for usage.
4. The projected usage and resulting fairshare score for an account based on a user specified job. Only calculates for CPU and Memory TRES.

## Contributing

Naturally any other useful slurm calculations can be added to this calculator.
