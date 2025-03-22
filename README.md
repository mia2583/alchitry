# alchitry

### 정리
[깃블로그](https://mia2583.github.io/categories/fpga/)

## Example 1
- 동작: rst 버튼 누를시에 led 점등

<p align="left">
  <img src="https://mia2583.github.io/assets/img/post/FPGA/alchitry_ex1.JPG", height="300x", width="300px">
</p>

## Example 2
- 동작: rst 버튼이 눌리면 led가 꺼지고, 누르지 않으면 led가 깜빡인다

<a href="https://mia2583.github.io/assets/img/post/FPGA/alchitry_ex2.mp4">
  <img src="https://github.com/user-attachments/assets/cf1cd9b4-30bf-4c96-ba9c-b3e54709d5b6", height="300x", width="200px">
  <img src="https://github.com/user-attachments/assets/94841d95-7321-45af-aecf-29f7738a9b93", height="300x", width="200px">
</a>


## Example 3
- 동작: 수신된 글자에 따라 다른 led 켜기
- 사용 컴포넌트 : UART Rx, UART Tx

<p align="left">
  <img src="https://mia2583.github.io/assets/img/post/FPGA/serial_terminal.png", height="100x", width="100px">
  <img src="https://mia2583.github.io/assets/img/post/FPGA/char_led.JPG", height="200x", width="200px">
</p>

## Example 4
- 동작: h 수신 시 Hello World! 송신
- 사용 컴포넌트 : UART Rx, UART Tx

<p align="left">
  <img src="https://mia2583.github.io/assets/img/post/FPGA/serial_terminal2.png", height="100x", width="100px">
</p>

## Example 5
- 동작: 입력을 기억하여 출력에 덧붙이기
- 사용 컴포넌트 : UART Rx, UART Tx, Simple RAM

<p align="left">
  <img src="https://mia2583.github.io/assets/img/post/FPGA/alchitry_ex5.png", height="100x", width="100px">
</p>

## Example 6, 7
MIG Wrapper (DDR3)
- 동작: 숫자 카운팅 LED로 표현하기
- Example7은 캐시 사용으로 더 빠르게 계산된다.

<a href="https://mia2583.github.io/assets/img/post/FPGA/alchitry_ex6.mp4">
  <img src="https://github.com/user-attachments/assets/eb8cd546-7ba1-415e-a867-05d137041d04", height="300x", width="300px">
  <img src="https://github.com/user-attachments/assets/3e2bd1d5-9b89-42db-8ff9-4a78e0cf9b04", height="300x", width="300px">
</a>

