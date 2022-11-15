<h2>index.jsp</h2>

![image](https://user-images.githubusercontent.com/97486359/201593090-85fb3435-9455-4d19-80d2-7ff7890b4b6f.png)

<h2>resv.jsp(백신예약)</h2>

![image](https://user-images.githubusercontent.com/97486359/201593208-ba75f39f-7991-4844-825a-c9b4c1004e18.png)

![image](https://user-images.githubusercontent.com/97486359/201811530-06cfd9f4-2994-4a6d-96c4-8c6b2f7e037d.png)

int num에 resvno의 최대 값을 +1를 입력합니다.

<h3>유효성검사</h3>

![image](https://user-images.githubusercontent.com/97486359/201792025-9fe88d12-fe3f-4fab-bf50-9ba2e0112bf3.png)

![image](https://user-images.githubusercontent.com/97486359/201811631-8bd7ab79-834d-43ee-88d9-bb2f9fa84a3a.png)

유효성검사를 이용해 빈칸이 있으면 알람 함수와 포커스을 발동합니다.

<h2>resvP.jsp(백신예약 데이터 전송)</h2>

![image](https://user-images.githubusercontent.com/97486359/201837628-67b08218-0a5d-423d-a877-ad4358f1d5bd.png)

resv.jsp에서 입력한 값을 PreparedStatement을 이용해 BD에 넣는 역할입니다. 

<h2>resv_list.jsp(예약리스트)</h2>

퀴리문
![image](https://user-images.githubusercontent.com/97486359/201838711-0f069bab-c34e-4696-9009-b49158441aeb.png)

![image](https://user-images.githubusercontent.com/97486359/201838763-aa308729-ded9-46ea-8252-9da0f64c5e34.png)

![image](https://user-images.githubusercontent.com/97486359/201838790-89618d6b-749d-4eba-a81c-87bf6109deeb.png)

반복문을 사용해서 DB안에있는 데이터를 차례대로 출력하는 jsp코드입니다.

<h2>resv_search.jsp(예약조회)</h2>

![image](https://user-images.githubusercontent.com/97486359/201840524-ac6182e2-1ada-4214-805a-e54bb205e3c9.png)

form태그를 이용해 테이블을 만든다.

<h3>유효성검사</h3>

![image](https://user-images.githubusercontent.com/97486359/201840875-4b3c5d63-e3f8-4575-b56a-4c2c678030c5.png)

![image](https://user-images.githubusercontent.com/97486359/201841045-1023fc47-ef92-41a3-a302-327dc207a834.png)

유효성검사를 이용해 빈칸이 있으면 알람 함수와 포커스을 발동합니다.

<h2>resv_search_list.jsp(예약조회 결과)</h2>

![image](https://user-images.githubusercontent.com/97486359/201841553-b83f6697-67e4-4f77-94ce-f4a49153c621.png)
내부 조인을 활용해 3개의 테이블을 합쳐 쿼리문을 작성합니다

![image](https://user-images.githubusercontent.com/97486359/201842314-705791c8-5024-4b31-96e3-757365af4422.png)

if문을 활용해 resv_search.jsp에서 넘어온 번호와 일치한 것과 일치 안한 결과를 화면에 각각 보여준다.

맞은경우<br>
![image](https://user-images.githubusercontent.com/97486359/201843176-0fb2f91d-a143-4af8-b71a-dada94af70ed.png)

틀린경우<br>
![image](https://user-images.githubusercontent.com/97486359/201843073-d58b24f3-c3ef-4af7-b98a-f2276ee4c26d.png)
