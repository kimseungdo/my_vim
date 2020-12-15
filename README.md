# my_vim
내 빔이다

# MD파일 사용법!
[^1]:문장의 끝에 스페이스바를 두번누르던지 엔터를 두번눌러야지 다음줄로 넘어갑니다.  
[^2]:# 을 이용하여 정할수 있으며 아래와 같이 #의 개수에 따라 크기가 달라집니다.  
[^3]:강조는 ** **을 강조하고 싶은 부분의 양쪽을 감싸주면 됩니다.**  
[^4]:기울임체는 *** ***을 기울이고 싶은 부분의 양쪽을 감싸주면 됩니다.***  
[^5]:취소선은 ~~ ~~을 취소선을 넣고싶은 부분의 양쪾을 감싸주면 됩니다.~~  
[^6]:코드 넣기 기능은 ''' ```언어 ```로 감싸주면 되고 자동 하이라이트를 지원합니다.  
[^7]:인용을 하려면 문장 앞에 >를 붙이면 됩니다.    

## 설정경로 : vi ~/.vimrc
set encoding=utf-8

set nu  
set autoindent  
set autowrite  
set autoread  
  
set cindent  
set smartindent  
set mouse=a  

set ts=4  
set shiftwidth=4  
set laststatus=2  
  
set colorcolumn=+1  
  
set ruler  
set hlsearch  
set incsearch  
set showmatch  
  
syntax on  
set foldmethod=indent  
set foldnestmax=1  
    
## ubuntu && debian pt5 tool chain  
build-essential  
apt-get purge --auto-remove libqt4-dev //기존 qt4 제거  
apt-get install qt4-qmake libqt4-dev // qt4 설치
apt-get install gcc-arm-none-eabi binutils-arm-none-eabi gdb-arm-none-eabi openocd // arm 설치  

  
## pip list  
pip install -m ~~~  
opencv-python  
Cython
jupyter  
keras  
lxml  
matplotlib  
numpy  
pandas  
pollow  
pyqt5  
tensorflow  
selenium  
