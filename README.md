# HTML 기본 코드에 대한 궁금점
문득 'shift + !'로 만들었던 HTML의 기본코드에 대해 궁금한 점들이이 생기기 시작했다.

## 기본코드
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

## < ! D O C T Y P E html> 
<em> </em>은 html의 버전이 무엇인지를 웹 브라우저에 알려주는 역할을 하는 선언문이다.
표준 html은 html5이기 때문에 DOCTYPE 뒤에 html은 html5을 의미한다. 

## <html lang="en">
lang 전역 특성은 요소 내의 수정 불가한 텍스트의 언어와, 수정 가능한 텍스트가 사용해야 하는 언어를 정의한다. 다시말해, lang 속성은 웹접근성에 관한 내용이다. head 요소 안에 페이지의 기본 언어 선언을 규정하고 있으며, 스크린 리더가 인식을 하여 시각 장애인을 위한 보이스 오버가 인식하는 언어를 나타낸다.

## <meta charset="UTF-8">
charset= "UTF-8"은 문서의 문자 인코딩 방식을 명시한다. UTF-8 문자 인코딩 방식은 1~4byte의 넉넉한 공간을 할당하여 인코딩하는 방식이다.

## <meta http-equiv="X-UA-Compatible" content="IE=edge">
content = "IE=edge"는 IE브라우저에서, 각 버전 중 가장 최신 표준모드를 선택하는 문서 호환성 모드이다. 문서 호환성 모드란 IE가 각 버전에 맞게 표준 모드로 제한 하는 것이다. 예를 들어 <meta http-equiv="X-UA-Compatible" content="IE=9">으로 IE버전을 선언하면, 가장 최신의 IE모드에서 IE9의 페이지에서 나타나는 것처럼 보이게 할 수 있는 것이다.

## <meta name="viewport" content="width=device-width, initial-scale=1.0">
meta 태그안의 정보들은 모바일 뷰포트를 위한 설정이다. 모바일 상에서의 보는 웹사이트의 뷰포트 크기를 맞추기 위해 이 정보를 선언한다.