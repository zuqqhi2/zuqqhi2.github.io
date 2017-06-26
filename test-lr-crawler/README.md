# Console log result(ideal case)

    ===== Learning Phase =====
    q-learning.js:68 Uncaught TypeError: Cannot read property 'randomAction' of undefined
        at QLearner.step (q-learning.js:68)
        at QLearner.learn (q-learning.js:79)
        at (index):124
    QLearner.step @ q-learning.js:68
    QLearner.learn @ q-learning.js:79
    (anonymous) @ (index):124
    (index):85 Epoch: 0 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 0 NG Count: 1
    (index):85 Epoch: 1 PrevState: 0 CurState: 2 Action: 3 Reward: 0 OK Count: 0 NG Count: 2
    (index):85 Epoch: 2 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 0 NG Count: 3
    (index):85 Epoch: 3 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 0 NG Count: 4
    (index):85 Epoch: 4 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 0 NG Count: 5
    (index):85 Epoch: 5 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 0 NG Count: 6
    (index):85 Epoch: 6 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 1 NG Count: 6
    (index):85 Epoch: 7 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 1 NG Count: 7
    (index):85 Epoch: 8 PrevState: 0 CurState: 2 Action: 3 Reward: 0 OK Count: 1 NG Count: 8
    (index):85 Epoch: 9 PrevState: 0 CurState: 2 Action: 3 Reward: 0 OK Count: 1 NG Count: 9
    (index):85 Epoch: 10 PrevState: 0 CurState: 2 Action: 3 Reward: 0 OK Count: 1 NG Count: 10
    (index):85 Epoch: 11 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 1 NG Count: 11
    (index):85 Epoch: 12 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 2 NG Count: 11
    (index):85 Epoch: 13 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 3 NG Count: 11
    (index):85 Epoch: 14 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 4 NG Count: 11
    (index):85 Epoch: 15 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 4 NG Count: 12
    (index):85 Epoch: 16 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 5 NG Count: 12
    (index):85 Epoch: 17 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 6 NG Count: 12
    (index):85 Epoch: 18 PrevState: 0 CurState: 2 Action: 0 Reward: 0 OK Count: 6 NG Count: 13
    (index):85 Epoch: 19 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 7 NG Count: 13
    (index):85 Epoch: 20 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 8 NG Count: 13
    (index):85 Epoch: 21 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 9 NG Count: 13
    (index):85 Epoch: 22 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 10 NG Count: 13
    (index):85 Epoch: 23 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 11 NG Count: 13
    (index):85 Epoch: 24 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 12 NG Count: 13
    (index):85 Epoch: 25 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 13 NG Count: 13
    (index):85 Epoch: 26 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 14 NG Count: 13
    (index):85 Epoch: 27 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 15 NG Count: 13
    (index):85 Epoch: 28 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 16 NG Count: 13
    (index):85 Epoch: 29 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 17 NG Count: 13
    (index):113 ===== Test Phase =====
    (index):85 Epoch: 30 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 1 NG Count: 0
    (index):85 Epoch: 31 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 2 NG Count: 0
    (index):85 Epoch: 32 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 3 NG Count: 0
    (index):85 Epoch: 33 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 4 NG Count: 0
    (index):85 Epoch: 34 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 5 NG Count: 0
    (index):85 Epoch: 35 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 6 NG Count: 0
    (index):85 Epoch: 36 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 7 NG Count: 0
    (index):85 Epoch: 37 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 8 NG Count: 0
    (index):85 Epoch: 38 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 9 NG Count: 0
    (index):85 Epoch: 39 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 10 NG Count: 0
    (index):85 Epoch: 40 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 11 NG Count: 0
    (index):85 Epoch: 41 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 12 NG Count: 0
    (index):85 Epoch: 42 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 13 NG Count: 0
    (index):85 Epoch: 43 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 14 NG Count: 0
    (index):85 Epoch: 44 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 15 NG Count: 0
    (index):85 Epoch: 45 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 16 NG Count: 0
    (index):85 Epoch: 46 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 17 NG Count: 0
    (index):85 Epoch: 47 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 18 NG Count: 0
    (index):85 Epoch: 48 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 19 NG Count: 0
    (index):85 Epoch: 49 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 20 NG Count: 0
    (index):85 Epoch: 50 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 21 NG Count: 0
    (index):85 Epoch: 51 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 22 NG Count: 0
    (index):85 Epoch: 52 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 23 NG Count: 0
    (index):85 Epoch: 53 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 24 NG Count: 0
    (index):85 Epoch: 54 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 25 NG Count: 0
    (index):85 Epoch: 55 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 26 NG Count: 0
    (index):85 Epoch: 56 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 27 NG Count: 0
    (index):85 Epoch: 57 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 28 NG Count: 0
    (index):85 Epoch: 58 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 29 NG Count: 0
    (index):85 Epoch: 59 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 30 NG Count: 0
    (index):85 Epoch: 60 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 31 NG Count: 0
    (index):85 Epoch: 61 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 32 NG Count: 0
    (index):85 Epoch: 62 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 33 NG Count: 0
    (index):85 Epoch: 63 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 34 NG Count: 0
    (index):85 Epoch: 64 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 35 NG Count: 0
    (index):85 Epoch: 65 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 36 NG Count: 0
    (index):85 Epoch: 66 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 37 NG Count: 0
    (index):85 Epoch: 67 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 38 NG Count: 0
    (index):85 Epoch: 68 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 39 NG Count: 0
    (index):85 Epoch: 69 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 40 NG Count: 0
    (index):85 Epoch: 70 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 41 NG Count: 0
    (index):85 Epoch: 71 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 42 NG Count: 0
    (index):85 Epoch: 72 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 43 NG Count: 0
    (index):85 Epoch: 73 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 44 NG Count: 0
    (index):85 Epoch: 74 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 45 NG Count: 0
    (index):85 Epoch: 75 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 46 NG Count: 0
    (index):85 Epoch: 76 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 47 NG Count: 0
    (index):85 Epoch: 77 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 48 NG Count: 0
    (index):85 Epoch: 78 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 49 NG Count: 0
    (index):85 Epoch: 79 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 50 NG Count: 0
    (index):85 Epoch: 80 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 51 NG Count: 0
    (index):85 Epoch: 81 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 52 NG Count: 0
    (index):85 Epoch: 82 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 53 NG Count: 0
    (index):85 Epoch: 83 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 54 NG Count: 0
    (index):85 Epoch: 84 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 55 NG Count: 0
    (index):85 Epoch: 85 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 56 NG Count: 0
    (index):85 Epoch: 86 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 57 NG Count: 0
    (index):85 Epoch: 87 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 58 NG Count: 0
    (index):85 Epoch: 88 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 59 NG Count: 0
    (index):85 Epoch: 89 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 60 NG Count: 0
    (index):85 Epoch: 90 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 61 NG Count: 0
    (index):85 Epoch: 91 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 62 NG Count: 0
    (index):85 Epoch: 92 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 63 NG Count: 0
    (index):85 Epoch: 93 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 64 NG Count: 0
    (index):85 Epoch: 94 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 65 NG Count: 0
    (index):85 Epoch: 95 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 66 NG Count: 0
    (index):85 Epoch: 96 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 67 NG Count: 0
    (index):85 Epoch: 97 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 68 NG Count: 0
    (index):85 Epoch: 98 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 69 NG Count: 0
    (index):85 Epoch: 99 PrevState: 0 CurState: 1 Action: 4 Reward: 10 OK Count: 70 NG Count: 0