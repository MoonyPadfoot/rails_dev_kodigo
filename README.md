# rails_dev_kodigo
git, rubymine, rails, and docker kodigo para sa ulianin

## git

- git init
  > initialize directory para makapag git
- git config --global user.name "Mama mo"
  > lagay username para sa git bash nimo
- git config --global user.email "email_ng_mama_mo@mail.com"
  > lagay email para sa git bash nimo
- git remote add origin https://github.com/OWNER/REPOSITORY.git
  > eto kapag may github repository ka na wala pang laman at gusto mong punan
- git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
  > eto kapag may github ka na mayroon ng laman at gusto mo kopyahin
- git add <file_name.extension> <file_name.extension>
  > pa isa isa ilagay ang di pa nalagay
- git add .
  > lagay mo lahat ng files
- git commit -m "description"
  > lagyan mo ng kahulugan ang mga files
- git commit -am "description"
  > short version ung add . at commit -m (gamit lang to kapag existing na ung file sa github)
- git push
  > sa local na computer mo push files
- git push origin
  > patungo sa github ang files
- git commit --amend
  > ung last commit na <description> pwede mong baguhin

## docker

- dkps
  > tignan ang mga running na container
- dcup
  > run ang docker container
- dcdw
  > idown ang docker container
- dkbu()
  > pag bagong project i build
- docker-compose exec <app_name> bash
  > pasok sa terminal ng docker dito mag rurun ng rails na command

## rubymine

- Shift + Shift
  > search ng files
- Alt + Shift + F
  > hanap ng words sa loob ng files
- Ctrl + G
  > highlight muna para ma select lahat ng kapareha na word
- Alt + Windows key + L
  > format code

## rails

- rails c
  > pasok sa loob ng rails console
- exit
  > labas sa rails console
