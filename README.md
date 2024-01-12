# 인생_비서 (life_secretary)

## Features 

00. splash & survey

* 스플래시 기능 (splash 앱 진입 후 로딩 기능)
* 로그인 기능 (OAuth)
    * 카카오 로그인
    * 구글 로그인
    * 애플 로그인
* 사용자 정보 입력(form) 및 선택(radio button) 기능
    * 닉네임
    * 생년월일 (o)
    * 성별 (o)
    * 결혼 여부
    * 직업군
    * 알고싶은 분야
* 약관 동의 및 가입 환영 인사

* 뒤로가기 기능 🤎

01. main

* 아티클 슬라이드(slide) 기능
* 대분류 각각 페이지 링크(link) - [대분류 아티클 리스트]
* 대분류 탭(tab)(버튼형) 기능
* 대분류 아티클 리스트 조회 기능 
    * 각각 아티클 상세 조회 페이지 링크(link)
    * 각각 아티클 스크랩 기능
→ 컴포넌트 활용 가능

* 그 외는 api 성격에 맞는 상세 페이지로 링크(link)
* 문의 및 의견 보내기 버튼

02. detail

[아티클 상세]
* 알림 설정 컨펌(confirm) - 진입시 알람 설정용
* 상세 페이지 markdown 형식 → HTML 형식으로 변경 기능 (?)
    * 추천 아티클 리스트 조회 기능
        * 각각 아티클 상세 조회 페이지 링크(link)
        * 각각 아티클 스크랩 기능
→ 컴포넌트 활용 가능

* 아티클 별점 생성(수정) 기능
* 아티클 공유 기능
* 아티클 스크랩 기능
* 아티클 스크랩 토스트 팝업 → 조금 웹뷰스럽다 ..?
* 아티클 대분류 키워드 관련 (다른) 아티클 리스트 페이지 링크(link)

[대분류 아티클 리스트]
* 대분류별 아티클 리스트 조회 기능 
    * 각각 아티클 상세 조회 페이지 링크(link) 💛
    * 각각 아티클 스크랩 기능 💛
* 대분류 셀렉트(select box) 기능
* 아티클 / 할 일 탭(tab) 기능 🧡
* 조회순 / 저장순 / 최신순 api 에 따른 아티클 정렬 기능 💚

* 뒤로가기 기능 🤎

 03. search

* 검색창(input) 기능
* 최근 검색어 생성 및 삭제 기능
    * 최근 검색어 더 보기 버튼
* 인기 검색어 리스트 조회 기능
    * 인기 검색어 관련 검색 결과 페이지 링크(link)

* 통합검색 / 할 일 탭(tab) 기능 🧡
* 검색 결과 조회 기능
    * 통합검색 
        * 각각 아티클 상세 조회 페이지 링크(link) 💛
        * 각각 아티클 스크랩 기능 💛
    * 할 일 
        * 할 일 추가(할 일 목록 수정) 기능 💙
        * 조회순 / 저장순 / 최신순 api 에 따른 아티클 정렬 기능 💚
* 검색 결과 없음 화면 💜

* 뒤로가기 기능 🤎

04. to-do

* 할 일 저장 목록 / 완료 목록 탭(tab)(버튼형) 기능
* (할 일) 저장 목록 
    * 리스트 조회 💙
    * (할 일) 상태 수정 기능 (to 완료) 💙
    * 할 일 없음 화면 💜
        * 할 일 보러가기 버튼 💜
* (할 일) 완료 목록 
    * 리스트 조회 💙
    * (할 일) 상태 수정 기능 (to 다시 할 일) 💙

* 할 일 생성 기능
    * 분야 선택(select box) 기능
    * 할일 타이틀 입력(input) 기능

05. save (scrap)

* 저장 목록 조회 기능
    * 각각 아티클 상세 조회 페이지 링크(link) 💛
    * 각각 아티클 스크랩 기능 💛
    * 저장 목록 없음 화면 💜
        * 아티클 보러가기 버튼 💜

* 저장 목록 삭제 기능
    * 각각 아티클 중복 선택 기능 💛

06. 관리

* 로그인 기능
* 로그아웃 기능
* 버전 정보 / 공지 사항 / 서비스 소개 / 제작자 소개 조회
* 회원 탈퇴 기능
* 문의하기 기능
    * 문의 내용 입력(input) 기능
    * 문의 메일 전송 기능
    * 전송 완료 팝업

* 뒤로가기 기능 🤎

## Collaborators ✨

<table>
    <tbody>
        <tr>
            <td align="center" valign="top" width="20%">
                <a href="https://github.com/bebe217">
                    <img src="https://github.com/ciocio97/life_secretary/assets/80025242/ee947e78-b6fe-464a-9991-5448bbe7893e" width="100px;" alt="thumbnail_jihye"/>
                    <br />
                    <sub><b>김지혜</b></sub>
                </a>
                <br /> 
                <a href="https://github.com/ciocio97/life_secretary/commits?author=bebe217" title="Documentation">
                📖
                </a> 
                <a href="https://github.com/ciocio97/life_secretary/pulls?q=is%3Apr+reviewed-by%3Abebe217" title="Reviewed Pull Requests">
                👀
                </a>
            </td>
            <td align="center" valign="top" width="20%">
                <a href="https://github.com/devsoladev">
                    <img src="https://github.com/ciocio97/life_secretary/assets/80025242/60f4d0fd-5c9e-4b6b-8cb4-500810f630d4" width="100px;" alt="thumbnail_sol"/>
                    <br />
                    <sub><b>안 솔</b></sub>
                </a>
                <br />
                <a href="https://github.com/ciocio97/life_secretary/commits?author=devsoladev" title="Documentation">
                📖
                </a> 
                <a href="https://github.com/ciocio97/life_secretary/pulls?q=is%3Apr+reviewed-by%3Adevsoladev" title="Reviewed Pull Requests">
                👀
                </a>
            </td>
            <td align="center" valign="top" width="20%">
                <a href="https://github.com/ciocio97">
                    <img src="https://github.com/ciocio97/life_secretary/assets/80025242/09fe7a4b-36b2-4d69-b175-8648f939ca33" width="100px;" alt="thumbnail_seungyeon"/>
                    <br />
                    <sub><b>이승연</b></sub>
                </a>
                <br />
                <a href="https://github.com/ciocio97/life_secretary/commits?author=ciocio97" title="Documentation">
                📖
                </a> 
                <a href="https://github.com/ciocio97/life_secretary/pulls?q=is%3Apr+reviewed-by%3Aciocio97" title="Reviewed Pull Requests">👀</a> <a href="#talk-ciocio97" title="Talks">
                📢
                </a>
            </td>
            <td align="center" valign="top" width="20%">
                <a href="https://github.com/hyeonjeong33">
                    <img src="https://github.com/ciocio97/life_secretary/assets/80025242/ed5119cb-0ecb-4069-ad85-df9736a116f3" width="100px;" alt="thumbnail_hyeonjeong"/>
                    <br />
                    <sub><b>전현정</b></sub>
                </a>
                <br /> 
                <a href="https://github.com/ciocio97/life_secretary/commits?author=hyeonjeong33" title="Documentation">
                📖
                </a> 
                <a href="https://github.com/ciocio97/life_secretary/pulls?q=is%3Apr+reviewed-by%3Ahyeonjeong33" title="Reviewed Pull Requests">
                👀
                </a>
            </td>
            <td align="center" valign="top" width="20%">
                <a href="https://github.com/KRjeonHyunji">
                    <img src="https://github.com/ciocio97/life_secretary/assets/80025242/b99e765b-edc7-4f69-8028-46eb7428fa1d" width="100px;" alt="thumbnail_hyeonji"/>
                    <br />
                    <sub><b>전현지</b></sub>
                </a>
                <br /> 
                <a href="#design-tbenning" title="Design">
                🎨
                </a>
            </td>
        </tr>
    </tbody>
</table>