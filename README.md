## 프로젝트 Build 과정

#### 1. Git 설치하기.
GitHub만 써왔던 내게, Git 자체는 조금 생소했다. 그래도 리눅스 관련 코딩을 했던 것을 생각을 하며 다시 새록새록 기억을 떠올리니 금방 적응할 수 있었다.

#### 2. 블로그용 repo 만들고, Jekyll 설치하기.
현재 Repository인 JW0705.github.io를 만들었다.
또한 git clone https://jw0705.github.io blog를 통해 클론을 만들어주고, 본격적인 작업에 들어가기 전 준비과정을 진행했다.
Ruby를 기반으로 한 Jekyll은 처음 보는 것이었으나, 막상 Jekyll로 터미널에서 다루는 언어는 생각보다 없고 소프트웨어적인 측면에서 큰 역할을 하는 것으로 보였다.

#### 3. 테마 다운로드하기.
나는 겉보기에도 이쁘고, 좋아하는 기능이 많이 있는 jekyll-theme-yat-master 의 theme을 다운받았다. 하지만 이것저것 기능이 많다보니 해당 테마 속의 내용물도 자연히 많을 수 밖에 없었고, 테마를 적용하는 데 자꾸 실패를 하기도 하고, 몇 가지 기능을 내가 원하는 대로 바꾸려고 하였으나 해당 부분을 담당하는 코드를 찾지 못하여 실패하는 부분이 많았다.

하지만 해당 테마의 README.md 파일을 통해 여러 시행착오를 겪으면서 Gemfile 에 `gem "jekyll-theme-yat"` 을, config.yml 에는  `theme: jekyll-theme-yat` 을 추가로 작성을 해야 한다는 점을 알고난 이후로 테마를 적용하였다. 하지만 역시나 마찬가지로, 기능을 내 입맛대로 바꾸는 데는 실패하였다.

#### 4. 댓글 적용하기.
강의를 따라서 Disqus를 이용하여 댓글을 적용할 수 있었다.
`comments = true` 인 경우에만 댓글을 작성 할 수 있도록 설정을 하였으며, 적용을 하고나서도 친구들에게 부탁하여 작성이 되는지 확인해보면서 신기함을 많이 느꼈다.

#### 5. favicon 적용하기.
favicon을 적용하기 위해서는 .ico 라는 확장자가 필요해서 우선 이미지를 32x32 사이즈로 만드는 사이트에서 이미지를 만들고, 이후에 favicon을 만드는 사이트에서 favicon을 제작했다.
그리고 구글링을 통해 `<head></head>` 구문에 favicon을 등록하는 코드를 넣으면 된다길래 넣었는데, 테마마다 조금씩 달라서 그런지 아니면 내가 favicon의 경로를 이상한 곳으로 설정을 해서 그런지 홈페이지의 좌상단 부분에만 favicon이 나오고 원하는 링크창이나 탭에는 favicon이 등록되지 않았다.

#### 6. Topic을 주제로 한 Post 작성하기.
**Markdown**을 이용하여 '_Git & GitHub, Markdown_ '에 대해서 작성해보았다. 아직은 Markdown에 서툴러서 Build 과정을 작성하는 것과, Post 둘 다 많이 사용하지도 않고, 조금 어색한 면이 존재한다.

#### 마치며.

블로그를 직접 만들어 보는 활동은 내 눈에도 코딩을 하는 결과가 시각적으로 보여서 즐거웠었다. 시간이 생긴다면 웹 관련 쪽으로도 공부를 해서 틈틈히 자신만의 블로그를 가꾸어나가고, 궁극적으로는 테마없이  스스로가 나만의 블로그를 만들어 보는 것이 목표가 될 것이다.
