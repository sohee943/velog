<p>컴퓨터 초기화 이후에 git 설정을 안했나보다...
다시<del>~</del></p>
<h3 id="git-설치하기window">Git 설치하기(Window)</h3>
<p>에러 시 원인을 찾기 위해 설치 중에 기본 세팅에서 내가 변경한 사항만 가져왔다. </p>
<ul>
<li><p>Use Visual Studio Code as Git's default editor
<img alt="" src="https://velog.velcdn.com/images/ssohopeful/post/97460803-a28b-42d2-bb55-6b2bbfdb3334/image.png" />
주로 사용하는 에디터인 VScode를 git의 기본 에디터로 설정했다. </p>
</li>
<li><p>Override the defualt branch name for new repositories
<img alt="" src="https://velog.velcdn.com/images/ssohopeful/post/b2968a95-e08a-4f4e-8831-7d599b078635/image.png" />
git의 main branch 이름을 'main'으로 설정했다. github의 기본 설정은 'main'인데 왜 git의 기본 설정은 'master'일까. Branch 이름 때문에 충돌이 일어난 적 있어서 수정했다.</p>
</li>
</ul>
<h3 id="git-계정-설정하기">Git 계정 설정하기</h3>
<p>명령어 <code>git</code> 을 입력해서 설치가 잘 되었는지 확인 후, 계정을 설정했다</p>
<pre><code>git config --global user.name &quot;유저 이름&quot;
git config --global user.email 유저이메일</code></pre><p><img alt="" src="https://velog.velcdn.com/images/ssohopeful/post/744f4f72-53f6-4454-81ac-eafc8074ca4d/image.png" /></p>
<h3 id="repository-생성-로컬에-복제">Repository 생성, 로컬에 복제</h3>
<p>github에서 생성한 repository를 로컬에 복제했다
복제할 위치로 이동 후 </p>
<pre><code>git clone 레포지터리경로</code></pre><p>해당 위치에 test_1이라는 폴더가 생성된다.
파일 탐색기에서 숨겨진 항목 보기를 선택하면
<img alt="" src="https://velog.velcdn.com/images/ssohopeful/post/c41dc8a0-ad0d-4c9f-b87a-f2fb12c766d1/image.png" />
위와 같이 .git 파일이 생성되었다</p>
<p>그 다음 .gitignore 파일을 생성했다. 어떤 내용을 만들지 정해지지 않았지만 미리 .gitignore을 만들어놔야 나중에 github에 업로드 되면 안되는 파일들을 까먹지 않고 제외할 수 있을 것같다.
<img alt="" src="https://velog.velcdn.com/images/ssohopeful/post/5d091b78-43d7-4fb4-a048-0009d38df88f/image.png" /></p>
<p>자 이제 프로젝트를 만들자</p>