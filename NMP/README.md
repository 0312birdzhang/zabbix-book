1.��RPM����ֻ֧��centos6.X RHEL6.X����������汾ϵͳ��������rpmbuild.
php��װ֮ǰ��ж��ϵͳ�Դ���php�汾
ж������Ϊ��rpm -qa|grep php|xargs rpm -e 
rpm -ivh \
libicu-4.2.1-9.1.el6_2.x86_64.rpm  \
libmcrypt-2.5.8-9.el6.x86_64.rpm    \     
libjpeg-turbo-1.2.1-1.el6.x86_64.rpm  \
libtidy-0.99.0-19.20070615.1.el6.x86_64.rpm  \
php-5.4.25-1.el6.x86_64.rpm

Ĭ���ѿ���php-fpm����(service php-fpm start)

