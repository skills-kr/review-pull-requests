## 1단계: 풀 리퀘스트 열기

_"Pull Request 리뷰하기"에 오신 것을 환영합니다! :wave:_

최근 `update-game` 브랜치에 추가된 변경 사항에 대해 **풀 리퀘스트**를 열어보겠습니다.

### 풀 리퀘스트란?

**풀 리퀘스트**는 한 브랜치의 작업을 다른 브랜치에 병합하기 전에 리뷰하는 협업 공간입니다. 대화를 관리하고 변경 사항을 쉽게 검토할 수 있는 여러 탭이 있습니다.

- **Conversation** - 풀 리퀘스트 활동의 전반적인 로그입니다. 동료 협업자와 커뮤니티가 아이디어, 제안, 일반적인 피드백을 제공할 수 있는 열린 공간이기도 합니다.
- **Commits** - 제안된 브랜치에만 있는 커밋 목록입니다.
- **Checks** - [GitHub Actions](https://github.com/features/actions)를 사용하여 풀 리퀘스트에 적용된 자동화의 결과입니다. 이건 다른 실습에서 다룹니다. 😎
- **Files Changed** - 제안된 변경 사항을 이전/이후 뷰로 쉽게 보여주는 [Diff](https://docs.github.com/en/get-started/quickstart/github-glossary#diff) 뷰입니다. 맥락에 맞는 댓글과 리뷰를 추가할 수 있는 옵션도 있습니다.

> [!TIP]
> 완료되지 않은 작업에 대해 [드래프트 풀 리퀘스트를 만들](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) 수 있습니다. 실수로 병합하거나 너무 이른 리뷰를 방지하는 데 도움이 됩니다.

### :keyboard: 실습: 풀 리퀘스트 만들기

1. 이 탭에서 안내를 읽으면서 작업할 수 있도록, 이 저장소를 새 브라우저 탭에서 여세요.

1. 상단 내비게이션에서 **Pull requests** 탭을 선택하세요.

1. 오른쪽에서 **New pull request** 버튼을 클릭하세요.

1. **Compare changes** 영역에서 다음 옵션을 선택하고 **Create pull request** 버튼을 클릭하세요.

   - **base:** `main`
   - **compare:** `update-game`

1. **제목**과 **설명**을 다음과 같이 설정하세요.

   ```md
   Update game over message
   ```

   ```md
   Update the game over message so people know how to play again!
   ```

1. **Create pull request**을 클릭하세요.

1. 풀 리퀘스트가 생성되면, Mona가 진행 상황을 확인하고 다음 단계를 안내합니다.
