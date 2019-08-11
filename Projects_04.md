# Projects_04

## 1. 01_layout.html

- 기초 레이아웃을 설정하고  Bootstrap을 활용하기 위해서 Bootstrap CSS, CDN을 <head>태그 안에 가져옵니다.

```html
 <!-- Bootstrap CSS -->
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>


</body>
  <!-- JS -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  <script src="https://kit.fontawesome.com/be859d7715.js"></script>
```

- navbar를 만들어주기 위해 다음과 같이 설정합니다. 일정 길이 이상에서만 오른쪽 세부 바의 구성요소가 나타나도록 설정합니다.

```html
    <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark">
      <a class="navbar-brand" href="#">영화추천시스템</a>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ml-auto">
          <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
          <a class="nav-item nav-link disabled" href="#">친구평점 보러가기</a>
          <a class="nav-item nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Login</a>
        </div>
      </div>
    </nav>
```

- footer 는 sticky-top으로 고정하여 스크롤을 올리거나 내려도 페이지의 맨 하단에 고정적으로 붙어서 디스플레이되도록 합니다.
- footer 내부에 있는 (1)작성자 정보 와 (2)Top 버튼을 각각 좌우 정렬될 수 있도록 div 안에 span으로 각각 지정하여 justify-content:space-between 를 적용해줍니다. Top의 버튼은 button 태그를 적용했습니다.

```html
    <footer class="sticky-top bg-dark">
      <div class="row" style="justify-content:space-between;"> 
        <span style="color:#FFFFFF;">Project #4 ⓒHanEol Lee, 2019</span>
        <span><a href="#top"><button class="btn bg-dark" style="color:#FFFFFF;"><strong>Top</strong></button></a></span>
      </div> 
    </footer>
```

## 2. 02_movie.html

- 내부 카드를 구성했습니다.

## 





.subtitle:after{

​    content:"";

​    display:block;

​    width:70px;

​    border-bottom: 3px solid rgb(156, 113, 33);

​    margin-left:auto;

​    margin-right:auto;

​    margin-top:10px;

  }

## 3. 03_detail_view.html

