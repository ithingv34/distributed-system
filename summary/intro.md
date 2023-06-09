# 분산시스템이란

**분산 시스템 사례**

- 대규모 기업들은 고도로 확장 가능한 대규모 분산 시스템을 운영하며 수 많은 사용자와 페타바이트 단위의 데이터를 처리하고 일정한 사용자 경험을 제공함

- 클라우드는 기업을 위해 구축된 복잡한 분산 시스템의 사례


**분산 시스템을 고려해야 하는 이유**

- 사용자가 늘어나면서 서버의 컴퓨터는 사용자의 요청과 저장할 데이터의 양이 늘어나게 된다.

- 컴퓨터의 성능을 높이는 `수직 확장` 방식을 고려할 수 있지만 근본적인 문제를 해결할 수 없음

- 서비스로의 트래픽이 계속해서 증가하면 성능과 메모리에 병목이 발생하며 서버를 업그레이드하는 한계에 직면하게 된다.

- 수평 확장을 통해 필요에 따라 시스템을 확장하거나 축소할 수 있어 서비스를 운영하는데 드는 비용의 효율을 높일 수 있다.


**분산 시스템이란**

- 분산 시스템은 네트워크를 통해 서로 통신하며, 서로 다른 컴퓨터에서 실행되는 여러 프로세스로 구성된 시스템으로 공동의 목표를 달성하기 위해 상태를 공유하거나 함께 작업하는 시스템이다.
  
- 다수의 서버를 사용하며 자원이 추가적으로 필요할 경우 서버를 추가할 수 있고 서버에 장애가 발생한 경우 나머지 프로세스들이 지속적으로 작업을 수행할 수 있는 시스템

- 프로세스를 분리하여 서로 다른
프로세스를 분리해 서로 다른 시스템에 배치하려면 프로세스들끼리 통신할 수 있도록 네트워크를 활용해야 한다.

- 프로세스들이 작업을 완료하기 위해 서로 상태를 공유하고 함께 작업하도록 만들어야 한다. 각 프로세스가 다른 프로세스의 상태에 대해 알지 못한다면 그것은 분산 시스템이 아니라 컴퓨터의 집합일 뿐이다. 
