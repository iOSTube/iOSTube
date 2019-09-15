## iOSTube

YouTube 앱을 참고해 샘플 앱을 구성하고 제법 사용해 볼법한 영상 재생 모듈을 만들어볼까 합니다.<br>
Swift, UIKit, AVPlayer, Github, Collabotation, ... 등 평소 공부하고 싶었던 내용을 다뤄보며 재밌게 진행하자구여!

### What Will We Make?

유투브 짝퉁(^_ㅠ) 앱을 만들고자 합니다. 슬프지만 디자인, 스펙 등의 상세는 아래 스크린샷으로 대체합니다 :(
<img width="800" src="/Resources/iOSTube-spec.jpeg">

우리의 iOSTube 는 크게 3부분으로 구성됩니다.  
1) Video List View
2) Video Detail View
3) Video Player View

위 화면을 순서대로 개발을 하되, 화면의 어느 부분을 개발하든 크게 상관없습니다.

단, 몇 가지의 참고 사항은 있습니다. 
* 영상의 다운로드를 제외한 API 통신은 Mock 데이터와 Stub 을 활용해 대체하려 합니다. 
* 샘플 일지라도 보이는 모습은 꽤나 중요합니다. 세부적인 디자인과 인터렉션에도 신경 씁시다.
* Task 를 할당할 때는 되도록 작은 단위로 쪼개어 진행합시다. 

### Develop Rules

**Swift Style**
* Raywenderlich/[Swift Style Guide](https://github.com/raywenderlich/swift-style-guide)

**Code Convention**
* GitHub/[Swift Style Guide](https://github.com/github/swift-style-guide)

**Git Convension**
* [Commit Message Guidelines](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53)
* [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.3/#summary)
* [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
* [좋은 git 커밋 메시지를 작성하기 위한 7가지 약속](https://meetup.toast.com/posts/106)
* [커밋 메시지로 이슈 닫기](http://minsone.github.io/git/github-commits-closing-issues-via-commit-messages)

**Review**
* [카카오스토리 팀의 코드 리뷰 도입 사례 – 코드 리뷰, 어디까지 해봤니?](https://tech.kakao.com/2016/02/04/code-review/)
* [코드리뷰, GitHub로 바로 적용하기](https://academy.realm.io/kr/posts/codereview-howto/)


