pkg update && pkg upgrade

pkg install git

termux-setup-storage

git clone https://github.com/xiaohaipa/XHP

cd XHP

chmod +x setup

bash setup

解包的文件放到:/storage/emulated/0/Download/obb_folder 解包出来的输出在:/storage/emulated/0/Download/output_folder 把要打包的uexp放在:/sdcard/Download/repack_folder
