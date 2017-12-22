//将默认资源库设置为淘宝镜像
gem sources --remove https://rubygems.org/
gem sources -a https://ruby.taobao.org/


gem sources --remove https://ruby.taobao.org/
gem sources -a http://gems.ruby-china.org


安装beta版本
gem install sass

升级sass版
gem update sass


sass -v
sass -h