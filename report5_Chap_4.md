# Report 5-2 [돌아가기_버튼](https://github.com/GomWoong/processing/blob/master/README.md)
## 안동대학교 김대현 
```

//4장. MakeFigure
void setup(){
  size(600, 400);
}

void draw(){
 fill(255, 255, 0);
 ellipse(300, 200, 200, 200); //얼굴
 fill(255);
 ellipse(250, 180, 50, 50); //눈
 ellipse(350, 180, 50, 50); //눈
 fill(0);
 ellipse(260, 190, 20, 20); //눈동자
 ellipse(340, 190, 20, 20); //눈동자
 fill(255, 0, 0);
 arc(300, 240, 100, 100, 0, PI); //입
}

```
### 설명
* 도형 만들기
* ellipse를 사용해 얼굴형, 눈, 눈동자를 생성
* arc를 사용해 입 구현
* 실행시 노란색 스마일 캐릭터가 나온다.
