# What is OS?

컴퓨터는 정보를 처리하는 기게
- 그럼 정보는 뭐임? $I(x) = -log_2P(x)$
    - 정보량은 정보가 일어날 확률의 log_2 를 붙인것과 같음.
    - 주사위로 예시를 들면,  **x = {1, 2, 3, 4, 5, 6}**, A 가 주사위를 던져서 3이 나온걸 B 라는 사람에게 알려줘야 할때 알려줘야 하는 정보는 무엇일까? 6/1 의 확률의 -log_2 를 하면 결국 전달해줘야 하는 정보량은 log_2 6 임을 알 수 있음

정보의 최소 단위 : **bit (binary digit)**
정보의 처리: 정보의 상태 변환 (0에서 1로, 1에서 0으로)
부울 대수: NOT, AND, OR
논리 게이트: NOT, AND, OR, XOR, NAND, NOR
논리 회로: IC, LSI, VLSI, ...
정보의 저장과 전송; **플립-플롭**, 데이터버스

컴퓨터는 정보를 어떻게 처리할까?
- 반가산기, 전가산기
- 뺄셈은 2의 보수법으로 표현
- 곱셈과 나눗셈은? 덧셈과 뺄셈의 반복
- 실수 연산은? 부동 소수점 표현법
- 함수는? GOTO

컴퓨터가 만능?
- 범용성
    - NOT, AND, OR 게이트만으로 모든 계산을 할 수 있다.
    - NAND 게이트만으로 모든 계산을 할 수 있다.
    - 범용 컴퓨터: general-purpose computer

- 계산가능성: computability
    - Turing-Computalbe: 튜링머신으로 계산가능한 것.
    - 정지 문제: Halting Problem: 튜링 머신으로 풀 수 없는 문제

컴퓨터를 만든 사람?
    - Alan Turing - Turing Machine
    - John von Neumann - ISA: Instruction Set Architecture

von Nenuman
    - A stored-program computer is 
        - a computer that store programs in a memory
    - ram 의 명령어를 CPU 가 가져와서 fetch -> execute
        - 이를 von Nenuman Architecture 라고 함.
    - 결국 우리가 사용하는건 von Nenuman Machine 이니까 program 이란 instruction 의 set 임.

운영체제도 프로그램의 일종
    - is a program running at all time on the computer
    - to provide system services to application programs
    - to manage processes, resources, user interfaces, and so on.