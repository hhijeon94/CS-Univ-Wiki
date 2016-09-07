# 도대체 왜 이것을 쓰게 되었는가?

여러 동아리를 다녀보면서 느끼는 건 많은 것들이 도제식 혹은 자기 주도 학습만으로 운영이 된다는 것입니다. 그리고, 이러한 구전이나 자기 학습이 가진 문제점들인 "소실"과 "변형"으로 인해서, 기술 단절이 생기고, 그로 인해 동아리가 장기적으로 운영될수록 땜질 같은 응급처치들이 쌓여가게 되며, 결과적으로 동아리 자체가 쇠퇴하는 것을 자주 보았습니다. 이에 대한 해결책으로 유지보수가 가능한 매뉴얼을 만들어서, 교육에 사용하자는 이야기가 나왔습니다만, 컴퓨터 공학, 특히 보안 분야에서는 이런 시도가 번번이 실패하는 경향을 보입니다. 넓디넓은 학문의 바다를 글로 표현하기에는 시간과 지면의 한계가 존재하고, 추세가 수년에서 심지어 6개월 단위로 바뀌는 IT나 정보 보안에 대한 이야기는 글로 풀어냄과 동시에 쓸모없는 것이 되어버리기 일쑤이죠. 하지만, 저는 그런데도 이 글을 작성하게 되었습니다. 컴퓨터 공학은 다양한 기저 학문과 타 학문의 영향을 많이 받아오면서 성장하였습니다. 현대 인터넷의 전신이라고 할 수 있는 아파넷과 하이퍼링크는 각각 군사 목적과 물리학 학회의 학술지 공유를 위해 탄생을 하였으며, 많은 물리학도, 수학도, 전산학도, 그리고 무어의 법칙과 같은 규모의 경제와 반도체 집적 기술의 향상과 같은 경영학적 개념이나 전자공학적인 부분의 도움을 받아 성장하였습니다. 저는 변하지 않았던 것들과 변할 수밖에 없는 것들, 그리고 이러한 흐름에 관해 이야기를 하고 싶습니다. 컴퓨터의 역사와 현재 무엇을 봐야 할지에 대해서, 1학년과 2학년들이 읽어나갈 수 있도록, 그리고 단기간에 유의미한 성장을 유도할 수 있도록, 제가 중요하다고 생각하는 것들을 적어나가는 그런 것이 될 거 같습니다 :)

이 글은 여러 개의 토막글로 이루어져 있습니다. 그 이유는 예상 독자가 3 종류로 구분이 되고 그에 따라서, 예상 독자가 각기 다른 글들을 쓰게 되었기 때문인데, 각 토막글의 주제는

1. 한양대생이라면 좀 알았으면 좋겠는 것
2. 컴퓨터 공학도라면 알았으면 좋겠는 것
3. 대학생이라면 알았으면 좋겠는 것

정도로 나눌 수 있을 것입니다. 3가지를 다 섞어서 이야기하기보다는 나눠서 이야기를 하는 게 낫겠다 생각을 하여, 주제별로 소분류를 만들고 순서에 상관없이 글을 읽어도 이해가 되도록 썼고, 만약 다른 토막글의 지식이 필요하다면 그 토막글을 주석이나 링크를 해 놓았으니 읽는 데에는 그렇게 큰 문제가 되지 않을 것으로 생각합니다.

# 그래서 뭘 쓰는가?

제가 대학에 와서 제일 처음 느낀 것은 __“도대체 대학에서 뭘 가르치는 것인가?”__ 였습니다. 사실 대학이 학문의 상아탑이라고들 하지만, 사실 많은 대학생들은 학문하려고 갔다기 보단 학교 타이틀이나 직장을 구하기 위해서 간 경우가 많고, 그에 따라서 대학교가 제공해주는 교육의 질이나 방식은 어느 정도 기업의 요구나 자본 논리에 의해 돌아 기기 시작했고, 또한 학생들의 인풋이나 공부에 대한 열의(1학년 때에는 놀아아죠 하핫!)도 영향을 받기 시작했죠. 거기다 3학년과 4학년이 되면, 전공과목보단 면접이나 인턴이 더 급하니 학문이라는 것을 제대로 배울 기회는 그렇게 길지도 않다는 것을 깨닫게 된 부분이 적잖이 있습니다. 으흠… 꼰대질하려고 쓰는 글이 아닌데 -_-;

하여튼, 저는 그런 상황에서 __군대에 안 가고, 학문이라는 것을 좀 해보고 싶다, 내가 그걸 미리 알았으면 좋았을 텐데, 이런 답이 안 나오는 거 같은 이상한 방식의 삶도 있다__는 걸 보여주고 싶었고, 그에 상응하는 (…) 좀 이상한 글을 쓰려고 합니다. 뭐 이 글을 읽고 있는 당신! 저와 같이 이상해져 보시고 싶으신가요?!

# Special Thanks to...

이 글에 조언을 해주신 모든 분들께...

# 기여하기

1. https://github.com/benjioh5/icewall-guideline 를 포크한다
2. 포크한 레포지토리에서 작업을 한다
   1. 내용 수정
   2. 커밋
   3. 수정하고 싶은 내용을 다 수정하였을 경우 푸시를 한다. 
3. 포크한 레포지토리에서 https://github.com/benjioh5/icewall-guideline 로 풀리퀘스트를 한다.
4. 관리자가 확인하고 제대로 수정이 되었으면 반영한다.