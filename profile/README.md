## 스마트 약품 관리 시스템

스마트 약품 관리 시스템은 2026년 진행한 인천대학교 학부생 3인의 캡스턴디자인 프로젝트입니다.
이 시스템은 사용자(환자)와 관리자(의료인)의 편의를 도와, 요양원 등 시설에서 환자의 원활한 복약 지도를 돕고
나아가 그 복약을 스마트 약품장을 포함한 시스템을 통해 간편히 진행하는 것을 목표로 합니다.

프로젝트는 약품장과의 상호작용을 담당하는 태블릿용 어플리케이션과, 약품장의 하드웨어부를 제어하는 아두이노,
웹캠을 통해 약품 등록을 자동화하는 Raspberry Pi와 이것들을 다루는 백엔드 서버로 이루어져 있습니다.

### 시스템 세부 사양
- 약품장 관리용 태블릿 어플_ Android app(developed by Android Studio) : [Android](https://github.com/CapstoneDesign-2026-SmartMediCabinet/Capstone_Tablet)  
- 아두이노 : [Arduino](https://github.com/CapstoneDesign-2026-SmartMediCabinet/Repo-Arduino)
- 웹캠 및 Ai Server : [python Flask](https://github.com/CapstoneDesign-2026-SmartMediCabinet/Repo-Rasberry)
- 로그인 및 메인 서버 : [Node.js](https://github.com/CapstoneDesign-2026-SmartMediCabinet/Server)
- 로컬 DB : mySQL; local 서버였기 때문에 repository 활용하지 않음

---
<details>
    <summary> MarkDown 문법 정리 : 참고용</summary>
    
  **참고용으로 작성하였으며, 준수하지 않으셔도 괜찮습니다.**  
  
  edit에서 작성하시고, preview로 결과 미리 보기 가능합니다. 줄바꿈할 때 문장 끝에 띄어쓰기(스페이스바) 두번!  
  이거 외에는 그냥 메모장처럼 슥슥 쓰셔도 됨

 ---
 # 1. 제목 (Headers)
 # 가장 큰 제목 (H1)
 ## 두 번째 제목 (H2)
 ### 세 번째 제목 (H3)

 # 2. 강조 (Emphasis)
*기울임* 또는 _기울임_
 **굵게** 또는 __굵게__
 ~~취소선~~
 **_굵고 기울임_**

 # 3. 목록 (Lists)
 - 순서 없는 목록은 하이픈(-)이나 별표(*)를 사용합니다.
    - 한 번 들여쓰면 하위 항목이 됩니다.

 1. 순서 있는 목록은 숫자를 씁니다.
 2. 자동으로 번호가 매겨집니다.

 # 4. 링크와 이미지 (Links & Images)
[구글 링크](https://www.google.com)
 ![이미지 설명](이미지_주소_입력)

 # 5. 코드 (Code)
 문장 속 `인라인 코드`는 백틱(`) 1개로 감쌉니다.   
 
  예) `print("Hello World)` 이런 식  

여러 줄의 코드는 백틱 3개로 감싸는 '코드 블록'을 사용합니다.
 ```python
 print("Hello World")

```

```c
int main(){
    printf("Hello, world!");
    return 0;
}
```

</details>


<details>
    <summary> 여기에 요약 제목 작성 </summary>
    
- 밑에는 내용이 들어감
</details>
