canGo
같은 색 말있는 곳으로는 못감
다른 색은 갈수 있음
폰 2칸 이동 구현

canAttack
canGo면서 거기에 상대 말 존재
예외 : 폰의 공격

moveAndAttack
이동뒤 해당 2치 위치를 위협가능.
이때 현재 위치에서는 공격이 불가능해야함
최종 공격 위치가 상대의 공격범위더라도 내가 반격 가능할때 ok
말들의 포인트를 지정할수있음

canGetPointHappy
손해 없이 잡을수있거나
그 위치가 공격범위더라도 내가 반격 가능할때

canGetPointSad
잡을수있지만 손해해가 따를때

checked
킹이 공격범위에 있을 경우

escapeCheck
킹을 옮기든
내 다른 말을 옮기든
어떻게든 왕을 안전하게

checkmate
체크상황에서
escapeCheck가 불가능

boardAfterMoving
잡으면서 움직이는거랑
그냥 움직이는거


dcgLocate

dcgCanAttack

dcgCanGo

dcgMoveAndAttack

dcgChecked
얘는 dcgAfterChecked랑 연결됨

dcgAfterChecked

dcgCanGetPoint
포인트가 1인지 아닌지에 따라 point뒤에 s가 붙음
