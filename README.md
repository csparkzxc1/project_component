# Mango_trick

### Button_component 개발일지



##### 목표

- 사용자의 접근성, 사용성을 높인다.
  - 클래스명의 직관성, 명료성
- ​

##### 개발도구

- scss 

##### 참고자료

- README.md (0201.md /.. )





---

# 개발순서

### 1단계 개별 모듈기능개발

- components 
  - card-box
  - button
- base
  - grid
  - layout



### 2단계

- _all.sass (components file)

```scss
@charset "utf-8"

@import "box.sass"
@import "button.sass"
```

- _all.sass (base file)

```scss
@charset "utf-8"

@import "grid.sass"
@import "layout.sass"
```



### 3단계 병합

- mango_trick.sass

```scss
@charset "utf-8"

@import "sass/base/_all"
@import "sass/components/_all"
```



### 4단계 컴파일

- mango_trick.sass 	=>	mango_trick.css