# MIA-calendar

## HOW TO USE
- 캘린더 영역 id를 생성자 함수의 인자로 생성자 함수 실행
- setDate로 표시할 날짜를 지정 (지정하지 않을 시 오늘 날짜)
```html
<div id="{ id }"></div>

<script type="text/javscript">
const calendar1 = new Calendar('{id}');
calendar1.setDate();

const calendar2 = new Calendar('{id}');
calendar2.setDate('2020-01-31'); // Y-m-d
</script>
```