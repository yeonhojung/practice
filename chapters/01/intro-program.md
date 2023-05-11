## 프로그래밍 언어 

### 데이터  

인간은 데이터를 수집하고 결합하여 분석을 하는 작업을 태어날 때부터 수행합니다. 우리가 사용할 수 있는 모든 감각 기관을 통해서 수집한 데이터는 뇌에 저장되고 처리됩니다. 이러한 과정을 통하여 인간은 
예측하고 결정하며 행동합니다. 이러한 인간의 능력을 컴퓨터로 구현하려는 학문이 기계학습(machine learning)과 인공지능(Artifical intelligence)입니다. 하지만 인간이 하는 일을 기계가 할 수 있게 하려면 아직도 먼 길이 남아 있습니다.

우리가 느끼고 보고 듣는 것들이 어떻게 인간의 뇌에 저장되는지는 아직도 잘 모릅니다. 하지만 우리는 다양한 자료를 컴퓨터에 저장할 수 있는 방법을 만들었고 이를 통상적으로 **데이터(data)** 라고 부릅니다. 특별히, 우리가 현재 말하는 데이터는 **디지털화된 자료** 로서  기본적으로 0과 1로, 즉 `BIT` 로 이루어진 자료입니다. IT 기술은 단순한 0과 1의 조합으로 다양한 데이터를 아주 많이 그리고 편리하게 저장할 수 있게 해 주었습니다.  

우리는 이 과목에서 컴퓨터를 이용하여 데이터를 디지털화하여 저장하고 변형/결합하여 **분석** 에 사용할 수 있는 유용한 것으로 만드는 프로그래밍의 기초를 배우려고 합니다.


### 프로그래밍 언어

**언어(language)는 소통입니다.**

사람들은 언어를 통하여 자신의 의사를 전달하고 타인의 생각을 이해하며 서로 소통합니다. 언어를 이용하여 상대방에 자신이 원하는 일을 시킬 수 있고 또한 언어를 통하여 자신의 생각과 수행한 일을 다른 사람에게 설명할 수 있습니다. 인간과 인간을 연결해주는 언어는 수 천 가지 종류가 있고(예를 들어 한국어, 영어, 일본어, 독일어 등) 언어를 표현하는 문자(writing system)와 문자들을 배열하는 규칙인 문법(grammar)이 있습니다. 예를 들어 우리는 영어를 사용하는 사람들과 소통하기 위하여 영어 단어를 외우고 문법을 익혀서 말하고 듣고 읽어서 의사를 전달하고 여러 가지 다양한 일을 수행합니다.

처음에 언급했듯이 프로그래밍 언어는 컴퓨터와 소통하기 위해서 개발된 언어입니다. 프로그래밍 언어도 인간 사이의 언어와 같이 언어를 구성하는 단어도 있으며 문법도 있습니다. 인간 사이의 언어 소통에서 단어를 잘못 선택하거나 문법이 틀리면 소통이 어려운 것과 마찬가지로 컴퓨터와 소통하는 경우에도 선택된 프로그래밍 언어의 단어와 문법에 맞게 사용해야 오류 없이 소통할 수 있습니다. 더욱 재미있는 것은 모국어가 아닌 다른 언어를 배우고 나서 오해 사용하지 않으면 단어와 문법에 서툴러지는 것처럼 프로그래밍 언어도 오래 사용하지 않는다면 같은 현상이 발생합니다.

**프로그래밍 언어(programming language)는 인간과 컴퓨터가 서로 소통하기 위한 언어입니다.**

프로그래밍 언어도 인간의 언어와 마찬가지로 하나만 있는 것이 아닙니다. 가장 초기에 나온 `Fortran` 언어가 있고 그 이후에 `C`, `Lisp`, `JAVA`, `R` 등 매우 많은 언어가 개발되었습니다. 이렇게 많은 프로그래밍 언어들 중에 무엇을 배울지 선택하는 것은 어려운 일입니다. 하디만 앞에서 언급했듯이 프로그래밍 언어는 인간의 언어와 매우 유사한 경향을 가지고 있습니다. 즉, 가장 많이 사용되는 언어를 배우면 여러 면에서 편리한 것처럼 프로그래밍 언어도 마찬가지입니다.

파이썬(python)은 1991년에 만들어진 비교적 역사가 짧은 언어이지만 최근 기계학습과 인공지능 분야에서 가장 활발하게 사용되는 범용 프로그래밍 언어(general-purpose programming langauge)입니다. 범용 언어라고 불리는 이유는 특정한 목적이 아닌 컴퓨터기 이용되는 전 분야에 걸쳐서 사용될 수 있기 때문입니다. 참고로 HTML, PHP와 같은 프로그래밍 언어는 은 웹페이지를 만드는 경우 주로 사용하려고 만든 특별한 목적을 가진 언어입니다.

앞에서 말했듯이 언어는 꾸준하게 사용하지 않으면 소통 능력이 떨어지게 됩니다. 여러분이 이 과목을 통하여 파이썬의 기초를 배우게 되지만 꾸준하게 사용하지 않는 다면 소통 능력이 떨어지게 되는 것을 기억하세요.

이제 우리는 현재 가장 널리 사용되고 있는 파이썬 언어를 배우고 이를 통해서 데이터를 다루는 기술을 익혀보려고 합니다.
