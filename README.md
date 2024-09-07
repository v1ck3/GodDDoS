#GodDDoS

GOD DDOS IS A SCRIPT WRITTEN IN GO LANGUAGE

INFO

    HTTP Get Flood
    HTTP Post Flood
    Random url(http get flood)
    Self edit header(You can use "nil" to use default header)
    Improved threading control
    More powerful flood
    Auto get ip form domain(golang inbuilt function)
    More format for random url(http get flood)
    Fixed for 386 systems

Default header setting:

    Random user-agents
    Random data(http post flood)
    Random Accpetall
    Random Referer(only for http get flood)

Download

apt install golang (for linux pc users)
pkg install golang (for termux users)

Then:

git clone https://github.com/v1ck3/GodDDoS.git

Header.txt format:

Accept: text/html
User-agent: Wget
Referer: http://google.com

Or anything else of http header. If you don't have any idea of this please just use "nil" for using default random header.
Usage

cd GodDDoS
go build GodDDoS.go
./GodDDoS  <url> <threads> <get/post> <seconds> <header.txt/nil>
