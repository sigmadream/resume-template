# 홍길동의 이력서

> 저는 OOO을 지망하고 있는 도술에 능숙한 개발자 홍길동 입니다. 현재 OOO을 기반으로 OOO을 진행하고 있으며, 즐겁고 신나는 개발팀과 함꼐 하기 위해서 수련을 정진하고 있습니다. 아직은 학생이라서, 팀을 구하고 있으니 관심있으시면 언제든 연락주세요!

----

## Installation & setup guide
윈도우 사용자를 위한 간략한 설치를 소개합니다.

- 필수 사항
  - [VS2022](https://visualstudio.microsoft.com/)
    - `C++`을 반드시 설치해주세요.
  - [scoop](https://scoop.sh/)
    - [윈도우 사용자를 위한 개발 환경 구성 #1](https://youtu.be/Z6YJfCzUZJE)을 참고하세요.

### Step 1 - 이력서 템플릿을 다운로드 하세요.
- [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)

### Step 2 - Ruby 2.7 버전 설치

```
$ scoop bucket add extras
$ scoop bucket add versions
$ scoop update
$ scoop search ruby
$ scoop install ruby26
$ scoop install msys2
$ ridk install
```

### Step 3 - Jekyll 설치

```
(modern-resume-theme-master) $ gem install bundler:2.1.4
(modern-resume-theme-master) $ bundle install
```

### Step 4 - Local에서 실행

```
(modern-resume-theme-master) $ bundle exec jekyll serve
fatal: not a git repository (or any of the parent directories): .git
Configuration file: D:/sd/Desktop/modern-resume-theme-master/_config.yml
            Source: D:/sd/Desktop/modern-resume-theme-master
       Destination: D:/sd/Desktop/modern-resume-theme-master/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.191 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'D:/sd/Desktop/modern-resume-theme-master'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.

```

----

## Ref

해당 저장소는 [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)을 수정하여 배포하였습니다. 해당 이력서에 대한 디자인 및 구조는 [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)을 참고하세요.

원본의 데모는 [View Demo](https://sproogen.github.io/modern-resume-theme/)에서 확인하실 수 있습니다.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
