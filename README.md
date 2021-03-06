# traceCollect

Open instructions for strace/ltrace to collect system calls for program analysis


## Intro:
The software repository is here:
http://sir.unl.edu/portal/index.php

This is where we get all the experiment programs and test cases.

The data we are trying to get is the system call and library call traces when those programs are executed. 
strace(http://linux.die.net/man/1/strace) and ltrace(http://linux.die.net/man/1/ltrace) for recording that data. 

Of couse it's ok if you have other ways to do it.


## Disclaimer
All implementations are only research prototypes!
Please use it only for tests.


## Reference
if you feel these instructions helpful, citing the papers:

```
@inproceedings{xu2015probabilistic,
  title={Probabilistic program modeling for high-precision anomaly classification},
  author={Xu, Kui and Yao, Danfeng Daphne and Ryder, Barbara G and Tian, Ke},
  booktitle={2015 IEEE 28th Computer Security Foundations Symposium (CSF)},
  pages={497--511},
  year={2015}
}
```

```
@inproceedings{xusharper,
  title={A Sharper Sense of Self: Probabilistic Reasoning of Program Behaviors for Anomaly Detection with Context Sensitivity},
  author={Xu, Kui and Tian, Ke and Yao, Danfeng Daphne and Ryder, Barbara G},
  booktitle={The 47th IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)},
  year={2016}
}
```
are highly aprreciated.
