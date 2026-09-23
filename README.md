# minitorch
The full minitorch student suite. 


To access the autograder: 

* Module 0: https://classroom.github.com/a/qDYKZff9
* Module 1: https://classroom.github.com/a/6TiImUiy
* Module 2: https://classroom.github.com/a/0ZHJeTA0
* Module 3: https://classroom.github.com/a/U5CMJec1
* Module 4: https://classroom.github.com/a/04QA6HZK
* Quizzes: https://classroom.github.com/a/bGcGc12k

## 1.5: Training

**Simple**

- Точки — 50
- Скрытые нейроны — 2
- Learning rate — 0.5
- Seed — 5
- Эпохи — 500

```text
Epoch: 10/500, loss: 30.8336, correct: 45/50
Epoch: 20/500, loss: 22.2287, correct: 49/50
Epoch: 30/500, loss: 11.1028, correct: 50/50
Epoch: 40/500, loss: 5.9571, correct: 50/50
Epoch: 50/500, loss: 3.8665, correct: 50/50
Epoch: 60/500, loss: 2.8362, correct: 50/50
Epoch: 70/500, loss: 2.2282, correct: 50/50
Epoch: 80/500, loss: 1.8327, correct: 50/50
Epoch: 90/500, loss: 1.5501, correct: 50/50
Epoch: 100/500, loss: 1.3391, correct: 50/50
Epoch: 110/500, loss: 1.1759, correct: 50/50
Epoch: 120/500, loss: 1.0469, correct: 50/50
Epoch: 130/500, loss: 0.9422, correct: 50/50
Epoch: 140/500, loss: 0.8551, correct: 50/50
Epoch: 150/500, loss: 0.7814, correct: 50/50
Epoch: 160/500, loss: 0.7183, correct: 50/50
Epoch: 170/500, loss: 0.6637, correct: 50/50
Epoch: 180/500, loss: 0.6160, correct: 50/50
Epoch: 190/500, loss: 0.5743, correct: 50/50
Epoch: 200/500, loss: 0.5377, correct: 50/50
Epoch: 210/500, loss: 0.5050, correct: 50/50
Epoch: 220/500, loss: 0.4758, correct: 50/50
Epoch: 230/500, loss: 0.4493, correct: 50/50
Epoch: 240/500, loss: 0.4254, correct: 50/50
Epoch: 250/500, loss: 0.4038, correct: 50/50
Epoch: 260/500, loss: 0.3840, correct: 50/50
Epoch: 270/500, loss: 0.3659, correct: 50/50
Epoch: 280/500, loss: 0.3492, correct: 50/50
Epoch: 290/500, loss: 0.3338, correct: 50/50
Epoch: 300/500, loss: 0.3195, correct: 50/50
Epoch: 310/500, loss: 0.3063, correct: 50/50
Epoch: 320/500, loss: 0.2940, correct: 50/50
Epoch: 330/500, loss: 0.2826, correct: 50/50
Epoch: 340/500, loss: 0.2719, correct: 50/50
Epoch: 350/500, loss: 0.2619, correct: 50/50
Epoch: 360/500, loss: 0.2525, correct: 50/50
Epoch: 370/500, loss: 0.2437, correct: 50/50
Epoch: 380/500, loss: 0.2354, correct: 50/50
Epoch: 390/500, loss: 0.2276, correct: 50/50
Epoch: 400/500, loss: 0.2202, correct: 50/50
Epoch: 410/500, loss: 0.2132, correct: 50/50
Epoch: 420/500, loss: 0.2067, correct: 50/50
Epoch: 430/500, loss: 0.2004, correct: 50/50
Epoch: 440/500, loss: 0.1945, correct: 50/50
Epoch: 450/500, loss: 0.1889, correct: 50/50
Epoch: 460/500, loss: 0.1835, correct: 50/50
Epoch: 470/500, loss: 0.1784, correct: 50/50
Epoch: 480/500, loss: 0.1736, correct: 50/50
Epoch: 490/500, loss: 0.1690, correct: 50/50
Epoch: 500/500, loss: 0.1646, correct: 50/50
```

**Diag**

- Точки — 50
- Скрытые нейроны — 2
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500

```text
Epoch: 10/500, loss: 11.5816, correct: 47/50
Epoch: 20/500, loss: 11.3618, correct: 47/50
Epoch: 30/500, loss: 11.3462, correct: 47/50
Epoch: 40/500, loss: 11.3434, correct: 47/50
Epoch: 50/500, loss: 11.3418, correct: 47/50
Epoch: 60/500, loss: 11.3403, correct: 47/50
Epoch: 70/500, loss: 11.3388, correct: 47/50
Epoch: 80/500, loss: 11.3372, correct: 47/50
Epoch: 90/500, loss: 11.3320, correct: 47/50
Epoch: 100/500, loss: 11.3127, correct: 47/50
Epoch: 110/500, loss: 11.2953, correct: 47/50
Epoch: 120/500, loss: 11.2769, correct: 47/50
Epoch: 130/500, loss: 11.2421, correct: 47/50
Epoch: 140/500, loss: 11.1703, correct: 47/50
Epoch: 150/500, loss: 11.0879, correct: 47/50
Epoch: 160/500, loss: 10.9807, correct: 47/50
Epoch: 170/500, loss: 10.8362, correct: 47/50
Epoch: 180/500, loss: 10.6352, correct: 47/50
Epoch: 190/500, loss: 10.3457, correct: 47/50
Epoch: 200/500, loss: 9.9316, correct: 47/50
Epoch: 210/500, loss: 9.3368, correct: 47/50
Epoch: 220/500, loss: 8.4844, correct: 47/50
Epoch: 230/500, loss: 7.3260, correct: 47/50
Epoch: 240/500, loss: 6.2138, correct: 47/50
Epoch: 250/500, loss: 5.5698, correct: 47/50
Epoch: 260/500, loss: 5.1726, correct: 47/50
Epoch: 270/500, loss: 4.6268, correct: 47/50
Epoch: 280/500, loss: 4.3201, correct: 47/50
Epoch: 290/500, loss: 3.9833, correct: 47/50
Epoch: 300/500, loss: 3.6163, correct: 47/50
Epoch: 310/500, loss: 3.4533, correct: 47/50
Epoch: 320/500, loss: 3.2138, correct: 47/50
Epoch: 330/500, loss: 2.9998, correct: 47/50
Epoch: 340/500, loss: 2.6894, correct: 47/50
Epoch: 350/500, loss: 2.5855, correct: 48/50
Epoch: 360/500, loss: 2.3388, correct: 50/50
Epoch: 370/500, loss: 2.2488, correct: 50/50
Epoch: 380/500, loss: 2.0451, correct: 50/50
Epoch: 390/500, loss: 1.9732, correct: 50/50
Epoch: 400/500, loss: 1.7960, correct: 50/50
Epoch: 410/500, loss: 1.7408, correct: 50/50
Epoch: 420/500, loss: 1.5839, correct: 50/50
Epoch: 430/500, loss: 1.5867, correct: 50/50
Epoch: 440/500, loss: 1.4568, correct: 50/50
Epoch: 450/500, loss: 1.4194, correct: 50/50
Epoch: 460/500, loss: 1.2643, correct: 50/50
Epoch: 470/500, loss: 1.2602, correct: 50/50
Epoch: 480/500, loss: 1.2138, correct: 50/50
Epoch: 490/500, loss: 1.0884, correct: 50/50
Epoch: 500/500, loss: 1.0774, correct: 50/50
```

**Split**

- Точки — 50
- Скрытые нейроны — 10
- Learning rate — 0.5
- Seed — 2
- Эпохи — 500

```text
Epoch: 10/500, loss: 25.5925, correct: 35/50
Epoch: 20/500, loss: 26.5114, correct: 35/50
Epoch: 30/500, loss: 26.5083, correct: 35/50
Epoch: 40/500, loss: 25.4133, correct: 35/50
Epoch: 50/500, loss: 24.1506, correct: 35/50
Epoch: 60/500, loss: 23.0788, correct: 35/50
Epoch: 70/500, loss: 21.8958, correct: 35/50
Epoch: 80/500, loss: 20.2680, correct: 36/50
Epoch: 90/500, loss: 19.0902, correct: 36/50
Epoch: 100/500, loss: 17.8850, correct: 38/50
Epoch: 110/500, loss: 16.9851, correct: 39/50
Epoch: 120/500, loss: 15.1426, correct: 43/50
Epoch: 130/500, loss: 14.1736, correct: 44/50
Epoch: 140/500, loss: 13.0482, correct: 45/50
Epoch: 150/500, loss: 11.3818, correct: 45/50
Epoch: 160/500, loss: 6.0278, correct: 47/50
Epoch: 170/500, loss: 4.4699, correct: 48/50
Epoch: 180/500, loss: 19.1123, correct: 39/50
Epoch: 190/500, loss: 3.6209, correct: 50/50
Epoch: 200/500, loss: 2.8176, correct: 50/50
Epoch: 210/500, loss: 2.3850, correct: 50/50
Epoch: 220/500, loss: 2.2853, correct: 50/50
Epoch: 230/500, loss: 2.1094, correct: 50/50
Epoch: 240/500, loss: 3.3495, correct: 48/50
Epoch: 250/500, loss: 3.5656, correct: 50/50
Epoch: 260/500, loss: 1.9953, correct: 50/50
Epoch: 270/500, loss: 1.6720, correct: 50/50
Epoch: 280/500, loss: 1.4046, correct: 50/50
Epoch: 290/500, loss: 1.1773, correct: 50/50
Epoch: 300/500, loss: 1.0532, correct: 50/50
Epoch: 310/500, loss: 0.9530, correct: 50/50
Epoch: 320/500, loss: 0.8738, correct: 50/50
Epoch: 330/500, loss: 0.8045, correct: 50/50
Epoch: 340/500, loss: 0.7437, correct: 50/50
Epoch: 350/500, loss: 0.6932, correct: 50/50
Epoch: 360/500, loss: 0.6485, correct: 50/50
Epoch: 370/500, loss: 0.6076, correct: 50/50
Epoch: 380/500, loss: 0.5703, correct: 50/50
Epoch: 390/500, loss: 0.5390, correct: 50/50
Epoch: 400/500, loss: 0.5090, correct: 50/50
Epoch: 410/500, loss: 0.4825, correct: 50/50
Epoch: 420/500, loss: 0.4585, correct: 50/50
Epoch: 430/500, loss: 0.4390, correct: 50/50
Epoch: 440/500, loss: 0.4159, correct: 50/50
Epoch: 450/500, loss: 0.3972, correct: 50/50
Epoch: 460/500, loss: 0.3824, correct: 50/50
Epoch: 470/500, loss: 0.3661, correct: 50/50
Epoch: 480/500, loss: 0.3492, correct: 50/50
Epoch: 490/500, loss: 0.3353, correct: 50/50
Epoch: 500/500, loss: 0.3224, correct: 50/50
```

**Xor**

- Точки — 50
- Скрытые нейроны — 10
- Learning rate — 0.5
- Seed — 5
- Эпохи — 500

```text
Epoch: 10/500, loss: 26.8457, correct: 40/50
Epoch: 20/500, loss: 20.4423, correct: 47/50
Epoch: 30/500, loss: 21.0904, correct: 39/50
Epoch: 40/500, loss: 12.5949, correct: 48/50
Epoch: 50/500, loss: 15.4262, correct: 42/50
Epoch: 60/500, loss: 8.7149, correct: 48/50
Epoch: 70/500, loss: 8.9261, correct: 46/50
Epoch: 80/500, loss: 5.8200, correct: 49/50
Epoch: 90/500, loss: 6.9097, correct: 47/50
Epoch: 100/500, loss: 3.8192, correct: 50/50
Epoch: 110/500, loss: 6.7652, correct: 47/50
Epoch: 120/500, loss: 3.1365, correct: 50/50
Epoch: 130/500, loss: 2.4434, correct: 50/50
Epoch: 140/500, loss: 2.3411, correct: 50/50
Epoch: 150/500, loss: 2.1256, correct: 50/50
Epoch: 160/500, loss: 1.9725, correct: 50/50
Epoch: 170/500, loss: 1.7416, correct: 50/50
Epoch: 180/500, loss: 1.5448, correct: 50/50
Epoch: 190/500, loss: 1.4049, correct: 50/50
Epoch: 200/500, loss: 1.3458, correct: 50/50
Epoch: 210/500, loss: 1.2099, correct: 50/50
Epoch: 220/500, loss: 1.1564, correct: 50/50
Epoch: 230/500, loss: 1.0522, correct: 50/50
Epoch: 240/500, loss: 0.9910, correct: 50/50
Epoch: 250/500, loss: 0.9212, correct: 50/50
Epoch: 260/500, loss: 0.8881, correct: 50/50
Epoch: 270/500, loss: 0.8401, correct: 50/50
Epoch: 280/500, loss: 0.7832, correct: 50/50
Epoch: 290/500, loss: 0.7463, correct: 50/50
Epoch: 300/500, loss: 0.6992, correct: 50/50
Epoch: 310/500, loss: 0.6773, correct: 50/50
Epoch: 320/500, loss: 0.6451, correct: 50/50
Epoch: 330/500, loss: 0.6037, correct: 50/50
Epoch: 340/500, loss: 0.5792, correct: 50/50
Epoch: 350/500, loss: 0.5520, correct: 50/50
Epoch: 360/500, loss: 0.5280, correct: 50/50
Epoch: 370/500, loss: 0.5061, correct: 50/50
Epoch: 380/500, loss: 0.4862, correct: 50/50
Epoch: 390/500, loss: 0.4671, correct: 50/50
Epoch: 400/500, loss: 0.4484, correct: 50/50
Epoch: 410/500, loss: 0.4314, correct: 50/50
Epoch: 420/500, loss: 0.4165, correct: 50/50
Epoch: 430/500, loss: 0.4021, correct: 50/50
Epoch: 440/500, loss: 0.3880, correct: 50/50
Epoch: 450/500, loss: 0.3746, correct: 50/50
Epoch: 460/500, loss: 0.3618, correct: 50/50
Epoch: 470/500, loss: 0.3491, correct: 50/50
Epoch: 480/500, loss: 0.3380, correct: 50/50
Epoch: 490/500, loss: 0.3283, correct: 50/50
Epoch: 500/500, loss: 0.3172, correct: 50/50
```

## 2.5: Training

**Simple**

- Точки — 50
- Скрытые нейроны — 2
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500
- Loss — 2.2849
- Правильные ответы на обучающих точках — 50/50
- Среднее время эпохи — 0.0412 с

**Diag**

- Точки — 50
- Скрытые нейроны — 2
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500
- Loss — 1.0958
- Правильные ответы на обучающих точках — 50/50
- Среднее время эпохи — 0.0431 с

**Split**

- Точки — 50
- Скрытые нейроны — 10
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500
- Loss — 1.9352
- Правильные ответы на обучающих точках — 49/50
- Среднее время эпохи — 0.2938 с

**Xor**

- Точки — 50
- Скрытые нейроны — 10
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500
- Loss — 3.9894
- Правильные ответы на обучающих точках — 48/50
- Среднее время эпохи — 0.2940 с

**Circle**

- Точки — 50
- Скрытые нейроны — 10
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500
- Loss — 3.7534
- Правильные ответы на обучающих точках — 49/50
- Среднее время эпохи — 0.3406 с

**Spiral**

- Точки — 50
- Скрытые нейроны — 10
- Learning rate — 0.5
- Seed — 0
- Эпохи — 500
- Loss — 33.6281
- Правильные ответы на обучающих точках — 29/50
- Среднее время эпохи — 0.3069 с
