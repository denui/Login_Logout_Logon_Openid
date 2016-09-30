# Login_Logout_Logon_Openid
# 1.Tạo thư mục chứa project
mkdir project
#
cd project
#
mkdir DEMO
# 2.Khởi tạo môi trường máy ảo
vitualenv mayao
# 3.chạy máy ảo
source mayao/bin/activate
# 4.Đến thư mục chứa file requirements.txt
cd cd DEMO/blog_login_v01
# 5.Cài đặt tất cả yêu cầu trong file requirements.txt vô máy ảo
pip install -r requirements.txt
# 6.Chạy lệnh để run project
./manage.py runserver
# hoặc
python manage.py runserver
# Note: do cài hết trên máy ảo nên muốn chạy project thỳ phải chạy máy ảo trước(3)
# muốn k phải chạy máy ảo thỳ cài thẳng vô máy thiệt =))
