Để chạy Hector SLAM :

$ roslaunch xe_4 hector.launch 

Phần sự án của nhóm em có 1 vấn đề để chạy navigaton bọn em cần thêm
 <broadcastTF>true</broadcastTF>
vào plugin của skid_steer nhưng nó sẽ gây ra lỗi TF_REPEATED_DATA
NÊN khi chạy slam cần chú thích phần này lại 


Ngoài ra có một số map khi load vào world thì bị trùng với vị trí robot nên cần thay đổi vị trí và map turtle bot đang bị lỗi 

Tạm thời phần localization của em còn một số lỗi chưa khắc phục 
