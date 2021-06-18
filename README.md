# Miniproject

### 프로젝트 소개 (메인 주제) 

시간이 많이 걸리지 않으면서 간단하게 즐길 수 있는 미니게임천국

#### 본인이 맡았던 기능

- 2048 게임
- 니편 내편 게임

#### 동영상 링크(유튜브 외부 링크) 및 섬네일 

<div>
	<a href="https://www.youtube.com/watch?v=4aJZRGXHV_A" target="_blank"><image src = "https://img.youtube.com/vi/4aJZRGXHV_A/mqdefault.jpg"></a>	
</div>



#### 사용한 api, ide 등의 버전

  JDK : 1.8
  IDE : Eclipse

  



#### 잘한 점 

그래픽 이동 기능 구현을 위해서 2D 그래픽에 대한 공부를 하였습니다.  

2048, 니편내편의 그래픽이 부드럽게 넘어가도록 설정했습니다.  

두 게임 특성상 키보드 움직임을 감지하는것 때문에 Key 다시 집중 공부를 해서

정상적으로 움직임을 할 수 있도록 했습니다.



처음 만든 그래픽 게임들이지만,  원하는 대로 작동했고, 에러없이 완료했습니다.



#### 힘들었던 점 

  - 공의 움직임을 구현할때 색깔과 내려오는 방식을 이해를 하지 못했다. 
   => 그래서 이 부분을 ArrayList를 참고하여 공의 크기 및 색깔들의 객체를 지정해서 해결했다.
   

  - 2048에서 크기 지정과 각각 2,4,8,16..등등의 색깔을 바꿀수없었다.
   => 그래서 이 부분을 객체 하나하나씩으로 바꿔서 색깔을 바꿨고, 크기 지정은 Double형에서 int 형으로 바꿔서 해결했다.
    

#### 부족한 점 (개선해야 할 점) 

  - 니편내편에서 공을 무한으로 내려오는 기능을 추가하려했으나 제한 시간 및 공의 처리 속도 이유로 구현하지 못했다. 

    => System.currentTimeMillis()를 사용하여 제한 시간을 60초에 도달하게 되면 게임이 끝나는 걸로 하면 될거같고, 공의 속도는  Keypressed를 다시 공부를 해서 구현하면 될 것같습니다.

  - 2048에서 Game over와 점수등을 추가를 하지 못했다.

    => Game over는 JOptionPane으로 다시 설정하면 될거같고, 점수는 2 + 2를 하게 되면 4가 만들어지는 방식이니 그 더해질때 그 값을 따와서 점수에다가 넣는 방식으로 만들면 될거같다.



#### 느낀 점

솔직하게 학원을 다니고 나서 미니 프로젝트를 시작한다고 해서 아직 많이 배운것도 없어서 내가 잘할 수 있을까라는 생각부터 시작했는데, 그래도 내가 최대한 할수있는 곳까지 가보고, 그때도 안되더라면 인터넷에서 참조를 하더라도 게임을 만들어야겠다라는 생각뿐이었다.

그렇지만, 첫 미니 프로젝트이기도 하고 인터넷에서 구글링을 해서 찾아서 하는 부분이 이게 과연 공부가 될까 라는 생각이었지만, 구글링을 하더라도 그 코드를 이해를 할 수 있어야 그 코드가 어떤식으로 작동 되는지를 알수있으니, 한번씩 찾아보면서 공부를 하게 되서 이렇게도 새로운 부분을 배울수있구나 라고 생각했다.

앞으로도 더 많은 프로젝트를 진행하겠지만, 첫 프로젝트보다 더 나은 결과물을 만들수 있도록 노력하겠습니다.

#### 프로젝트 사용 화면

![KakaoTalk_20210618_001328392](https://user-images.githubusercontent.com/83326077/122445143-35f5fb80-cfdc-11eb-989e-f2371d114ee2.png)


#### Javadoc 링크(repo 내부 링크)

https://kimsangya.github.io/Megaminiproject/doc/index.html 

