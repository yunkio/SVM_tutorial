# Support Vector Machine 튜토리얼

> 서포트 벡터 머신 (SVM) 튜토리얼 페이지 입니다. 



![image](https://user-images.githubusercontent.com/35906602/199677064-9756f628-0d99-464b-b070-70aab8d47484.png)
https://m.blog.naver.com/slykid/221716780045

**서포트 벡터 머신 (SVM)** 은 데이터의 클래스를 분류하기 위한 결정 경계 (Decision Boundary)를 정의하는 모델입니다. 두 클래스를 분류 해내는 마진을 최대화 하는 결정 경계를 찾는 것을 목적으로 합니다.

![image](https://user-images.githubusercontent.com/35906602/199677557-3de1ad61-8885-4f04-b3ff-548957493a3b.png)
https://medium.com/@zxr.nju/what-is-the-kernel-trick-why-is-it-important-98a98db0961d

따라서 SVM은 기본적으로는 선형 분류라고 할 수 있습니다. 하지만 데이터를 선형 분류기로 분류 해낼 수 없는 경우가 많습니다. 이러한 한계를 극복하기 위해 적용된 것이 **커널 트릭 (Kernel Trick)** 입니다. 데이터를 원본보다 더 높은 고차원으로 맵핑시키는 방법입니다. 커널 트릭을 활용한다면 위와 같이 선형 분류가 불가능한 2차원의 데이터를 3차원으로 맵핑하여 분류하는 식의 활용이 가능합니다.

더욱 자세한 설명은 [Notebook](https://github.com/yunkio/SVM_tutorial/blob/main/Tutorial.ipynb)을 참고 해주세요.

![image](https://user-images.githubusercontent.com/35906602/199675574-a71deb42-b68b-4d38-a973-11e2e81c8e88.png)

![image](https://user-images.githubusercontent.com/35906602/199676223-6cd04c5f-e058-4d98-beb6-3bd3202a19a4.png)
