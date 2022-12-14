## Ch.2 퍼셉트론

### 2.1 퍼셉트론이란?

다수의 입력에 가중치를 곱하여 더한 값이 임계값 \theta보다 크면 1, 작거나 같으면 0을 출력하는 함수.<br>

### 2.2 단순한 논리회로 구현

가중치나 임계값 등의 매개변수(Parameter)는 인간이 설정한다.<br>
이를 자동으로 기계가 하는 걸 기계학습이라 한다.<br>

### 2.3 퍼셉트론 구현하기

    def AND(x1, y1):
        x = np.array([x1, x2])
        w = np.array([0.5, 0.5])
        b = -0.7
        tmp = np.sum(w*x) + b
        if tmp > 0
            return 1
        elif tmp <= 0
            return 0

### 2.4 (단층)퍼셉트론의 한계

선형만 표현 가능하며 비선형 함수는 표현할 수 없다.<br>

### 2.5 다층 퍼셉트론

XOR 같은 비선형 함수도 퍼셉트론을 여러 층으로 쌓아 구현 가능하다.<br>

### 2.6 NAND에서 컴퓨터까지

NAND는 퍼셉트론으로 구현 가능한데, 컴퓨터를 NAND만으로 만들 수 있다.<br>
따라서 컴퓨터 또한 다층 퍼셉트론으로 구현 가능하며, 이론적으로 2층 퍼셉트론으로 모든 함수 표현 가능하다.<br>
