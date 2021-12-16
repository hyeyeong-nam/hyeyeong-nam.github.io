# 유레카 프로젝트
## 이 블로그는 2021 유레카 프로젝트를 위해 제작된 블로그입니다.
It is a Jekyll theme based on [butane-jekyll-theme](https://github.com/alexcarpenter/butane-jekyll-theme) by @alexcarpenter

## 1. README.md를 만들자
README.md 파일은 두 가지 방법으로 생성할 수 있습니다.

1-1. 첫 번째 방법은 Repository를 처음 만들면 나오는 방법에 따라 코드를 작성하여 만드는 것입니다.

1-2. 
```
echo "# Repository의 이름" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hyeyeong-nam/Repository의 이름.git
git push -u origin main
```

1.3 1-2의 방법을 따른다면 README.md를 만들 수 있습니다.

2-1. 두 번째 방법은 creating a new file이라는 문장을 눌러 만들 수 있습니다.

2-2. 이미 다른 파일이 있는 상태라면 Add file의 creat new file을 눌러 만들 수 있습니다.

2-3. 저는 이 방법을 통해 README.md를 만들었습니다.

## 2. 테마 적용하기

1-1. 먼저 대부분 사용하는 내용에 대해 알아보겠습니다.

1-2. Jeky11 테마를 적용하기 위해서는 먼저 Ruby를 설치해야 합니다. 

1-3. https://jekyllrb.com/ <- 이곳으로 가게 되면 자세한 설명과 함께 설치를 할 수 있는 사이트로 갈 수 있습니다.

1-4. 설치를 다 마치고 나면 다음과 같은 코드를 통해 Jeky11은 물론 종속되어 있는 라이브러리를 설치할 수 있게 됩니다.
```
gem install jekyll
gem install jekyll-feed
gem install bundle
gem install github-pages
gem install tzinfo-data
gem install bundler minima rdiscount
```

1-5.  http://jekyllthemes.org/ <- 이곳에서 마음에 테마를 검색한 다음과 같은 과정을 거쳐 적용합니다.
```
1. 디렉토리에서 jekyll new <폴더 이름>이라는 명령어를 입력합니다.
2. 해당 폴더에서 GEM파일을 연 뒤 gem을 jekyll-theme-clean-blog로 변경합니다.
3. bundle install을 통해 테마를 설치합니다.
4. 해당 폴데에서  _config.yml 파일을 jekyll-theme-clean-blog로 변경합니다.
5. bundle exec jekyll serve을 통해 사이트를 설치합니다.
```

1-6. 해당 사항들을 끝내면 서버가 잘 돌아가는지 확인하고 자신의 Repository에 올립니다.



