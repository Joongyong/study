# 객체의 생성과 삭제

Topic.
1. 객체를 만들어야 하는 시점과 그 방법
2. 객체 생성을 피해야 하는 경우와 그 방법
3. 적절한 순간에 객체가 삭제되도록 보장하는 방법
4. 삭제 전에 반드시 이루어져야 하는 청소 작업들을 관리하는 방법

## 규칙 1 - 생성자 대신 정적 팩토리 메서드를 사용할 수 없는지 생각해 보라
클래스를 통해 객체를 만드는 일반적인 방법은 public으로 선언된 생성자를 이용하는것.
##### 방법이 하나 더 있다!
클래스에 public으로 선언된 정적 팩토리 메서드`(static factory method)` 를 추가하는것.

Welcome to StackEdit!
===================


Hey! I'm your first Markdown document in **StackEdit**[^stackedit]. Don't delete me, I'm very helpful! I can be recovered anyway in the **Utils** tab of the <i class="icon-cog"></i> **Settings** dialog.