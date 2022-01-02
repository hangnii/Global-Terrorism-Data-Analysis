# Global Terrorism Data Analysis
<br/>

## 1. 프로젝트 개요
- 1970~2010년대에 발생한 전세계의 **테러**데이터를 다양한 관점에서 분석하는 프로젝트
- 사용한 데이터 
  -  **Global Terrorism Database** - More than 180,000 terrorist attacks worldwide, 1970-2017(https://www.kaggle.com/START-UMD/gtd)
<br/>

## 2. 연도별 테러발생 수

![image](https://user-images.githubusercontent.com/92846399/147870725-36c3c2d3-9c26-4325-8499-b4cadcd05063.png)
  
>- **1980년대 후반 ~ 1990년대 초반** : 상승세를 보이다가 다시 감소
>- 2000년대 중반부터 다시 점차 상승세를 보이다가 **2010년대**에 접어들면서 <u>가파른 상승세</u>
>- 각각의 상승세는 '911테러'와 'IS' 때문일까?
<br/>

## 3. 테러발생 상위10개 국가 분석
<div align="center">
  
![image](https://user-images.githubusercontent.com/92846399/147870806-d9bb3875-1b0c-4bec-aa53-3ea7626513b0.png)
  <br/>
  
상위10개 국가별 사망자/부상자 수(바 차트)
![image](https://user-images.githubusercontent.com/92846399/147870822-3601c2c6-4d79-4ff2-a3ad-ee1c3dd93b14.png)
  <br/>
  
상위10개 국가별 사망자/부상자 수(파이 차트)
![image](https://user-images.githubusercontent.com/92846399/147870845-d66b2eb4-4818-4081-b26a-6e0d490c906d.png)
  </div>
  
>- 사망자 수가 부상자 수 보다 많은, 즉 50%를 넘기는 나라들은 **'콜롬비아', '페루', '엘살바도르'** 이다.
>- 이 세나라는 모두 **중남미**에 위치한다.

<div align="center">
  <br/>
상위 10국가별 테러 발생 대비 사상자 수
  
![image](https://user-images.githubusercontent.com/92846399/147870891-33ef102b-c8b6-46bc-88b1-30f946e181b8.png)
  </div>
  <br/>
 
## 4. 권역별 분석
![image](https://user-images.githubusercontent.com/92846399/147870925-f2ce6fb2-3c93-4d92-b205-aaef65e345f5.png)
<br/>
<div align="center"> 
<br/>
권역별 사망자 수/부상자 수 비교
  
<p align="center"> 
<img src="https://user-images.githubusercontent.com/92846399/147870938-a0571b61-3a43-4822-b9a2-a36824662116.png" width="60%" height="60%"/>
  </p>
<br/>
  
![image](https://user-images.githubusercontent.com/92846399/147870942-ecd84224-4078-47ed-a244-bfab1b356e89.png)
</div>

> - 절대적 수치를 보면 **중동&북아프리카** 권역의 사상자 수가 압도적으로 많으며, **남아시아** 권역이 두 번째로 사상자 수가 많다.
> - 남아메리카는 세 번째로 사상자 수가 많은 권역인데, 8개의 권역 중 유일하게 **남아메리카**만 사망자 수가 부상자 수보다 많다.
> - **북미와 서유럽, 동아시아**와 같이 상대적으로 선진화된 권역들은 전체 사상자 중 사망자 수가 적은 비중으로 나타난다.

<br/>
<div align="center"> 
  
권역별 공격형태 (바 차트)
  
![image](https://user-images.githubusercontent.com/92846399/147871647-8f6a61fe-86af-468d-bfdf-e0001cc81145.png)
</div>

>- 대부분의 권역에서 **'폭탄 테러'**와 **'무장공격'**이 가장 빈번한 공격형태

<br/>
<div align="center"> 
권역별 공격형태 (파이 차트)
  
![image](https://user-images.githubusercontent.com/92846399/147871651-ac2f3d17-26fa-47e7-865a-47622ac7b0f2.png)
</div>

>- **서유럽, 북아메리카, 동아시아** : 다른 권역보다 **시설,인프라 공격** 비중이 높고, 무장공격의 비중이 낮은 편
=> **사망자 수가 비교적 적은 이유!**

<br/>
<div align="center"> 
권역별 무기 종류

![image](https://user-images.githubusercontent.com/92846399/147871719-2a495823-1f5a-40e1-9e0f-4e077c52a856.png)
<br/>
</div>

## 5. 연도별 테러 형태 분석
<div align="center"> 
  
연도별 테러 세력

![image](https://user-images.githubusercontent.com/92846399/147872579-8cd5b19e-69a6-4e1e-b57b-4711defa1162.png)

<br/>
  
연도별 테러 대상

  ![image](https://user-images.githubusercontent.com/92846399/147872601-757d63a5-56e3-478a-a17a-72260f6a2352.png)
<br/>
  
2012년 전후 지역별 테러 사상자
  
![image](https://user-images.githubusercontent.com/92846399/147872644-5772bbb8-8b24-4feb-a8db-73f7b934bb49.png)

</div>

> - 전반적으로 모든 지역에서 사망자 수와 부상자 수 모두 2012년 이후로 감소하는 양상을 보인다.

> - 그러나 사상자 수 발생 상위 두 지역을 보면, 
   중동&북아프리카는 2012년 이후로 사망자 수가 증가한 유일한 지역이며, 
   남아시아 역시 감소하긴 했지만 그 폭이 큰 편은 아니다.

> - 남아메리카 지역이 사망자와 부상자 수 모두 가장 큰 폭으로 감소하였다.

> - 2012년 이후 서유럽과 북아메리카는 사망자 수가 현저히 감소하였으며, 
   부상자 수 역시 사망자 수보다는 많지만 비교적 적은 편이다.

> - 동아시아는 시기와 상관없이 사망자 수가 가장 적은 지역이며, 부상자 수도 2012년 이후로 상당히 감소하였다. 
   이는 다른 지역에 비해 이슬람세력의 테러가 적은 것도 이유가 될 수 있다.

> - 동유럽은 서유럽과 비교했을 때, 2012년 이전의 사상자 수는 적지만, 2012년 이후의 사상자 수는 더 많다.
   또한 하위 5지역 중에선 가장 감소폭이 적은 것으로 보인다.

> - 남동아시아 지역은 하위 5지역 중 2012년 이후 가장 사상자 수가 많은 것으로 보인다.

> - 테러가 발생했을 때 피해를 받는 규모와 대처 면에서 국가의 경제력이 영향을 끼칠 수 밖에 없을 것이므로, 
   이러한 결과가 나타난 것이라 예상해볼 수 있다.

<br/>
<div align="center"> 

지역별 시기별 사상자 수

![image](https://user-images.githubusercontent.com/92846399/147872438-99264743-5e7f-4a36-90d8-0ff42daebed2.png)

</div>
  
> - 중동&북아프리카와 남아시아는 시간이 지남에 따라 테러로 인한 사상자 수가 
   계속 가파르게 상승 중이며, 2010년대의 사상자가 가장 많음.

> - 남아메리카는 1980년대의 사상자수가 가장 많았고, 이후로 가파르게 감소.

> - 서유럽 역시 1980년대가 가장 많았고, 이후 완만한 감소세.

> - 남동아시아는 상위 두 지역에 비해 사상자 규모가 크진 않지만, 
   역시 시기가 지남에 따라 계속 증가 양상.

> - 동유럽은 2000년대에 가장 많았고, 2010년대에 약간 감소하였으나 비슷한 규모를 유지.

> - 북아메리카는 2000년대만 우뚝 솟아 있는데, 911테러로 인한 것이라 추측.

> - 동아시아는 1990년대가 독보적. 


<div align="center"> 
  
지역별 시기별 공격형태
  
![image](https://user-images.githubusercontent.com/92846399/147872561-60a16c4e-ac3d-4d82-8e70-797b6d5516b2.png)



</div>

>- 전반적으로 중동&북아프리카, 남아시아, 남동아시아에서는 모든 형태의 테러공격이 가파르게 상승 중.
>- 특이점
>  -  7-80년대 서유럽, 80년대 남미 : **'암살'** 많음.
>  -  서유럽, 북미 : **'시설공격'** 많음.

![image](https://user-images.githubusercontent.com/92846399/147872402-702fc219-20f3-4ad1-b1c2-4cb5ce57d356.png)


  
