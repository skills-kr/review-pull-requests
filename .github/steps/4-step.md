## 4단계: 변경 사항 제안하기

_풀 리퀘스트 리뷰를 잘 하셨습니다 :sparkles:_

리뷰 중에 설명하기보다 직접 구현하는 것이 더 쉬운 간단한 변경 사항을 발견하는 것은 매우 흔한 일입니다. 예를 들어, 오타나 문장 재구성 같은 것들이 있습니다. 이런 상황에 **Add a suggestion** 기능이 딱 맞습니다.

### 변경 사항을 어떻게 제안하나요?

**Add a suggestion** 기능은 댓글 텍스트 편집기에 있는 버튼입니다. 특별한 형식의 코드 블록을 삽입합니다. 단순히 댓글만 보여주는 것이 아니라, GitHub이 **Commit changes** 버튼도 함께 제공합니다. 이를 통해 저자가 버튼 하나로 제안을 수락하고 커밋할 수 있습니다. 코드 편집기를 열 필요가 없습니다!

### :keyboard: 실습: 변경 사항 제안하기

1. 풀 리퀘스트에서 **Files changed**를 클릭하세요.

1. `index.html` 파일의 비교 뷰를 찾으세요.

1. 수정된 줄의 줄 번호 옆에 커서를 올리세요.

1. 플러스 아이콘을 클릭하여 인라인 댓글 양식을 표시하세요.

1. **Add a suggestion** 버튼을 클릭하여 수정 가능한 줄의 복사본을 삽입하세요.

   <img width="300" alt="add-a-suggestion-button" src="https://raw.githubusercontent.com/skills-kr/review-pull-requests/main/.github/images/add-a-suggestion-button.png" />

1. 제안을 아래와 같이 수정하고 **Add a single comment** 버튼을 클릭하세요.

   ````md
   ```suggestion
   <h2 hidden>Game over! Want to play again?! Just click refresh. 🧑‍🚀!</h2>
   ```
   좀 더 친근하게 만들어 봅시다. 🤓
   ````

### :keyboard: 실습: 제안된 변경 사항 적용하기

1. **Commit suggestion** 버튼을 클릭하여 커밋 메시지 양식을 여세요.

1. 커밋 메시지를 아래 텍스트로 수정하고 **Commit changes** 버튼을 클릭하세요.

   ```markdown
   Make the end game experience more friendly
   ```

1. 변경 사항이 커밋되면, Mona가 진행 상황을 확인하고 다음 단계를 안내합니다.
