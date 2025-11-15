1. 实验目的
掌握 Shell 脚本的文件遍历、条件判断、变量操作等核心语法；
学会使用 for 循环和 mv 命令实现文件批量重命名；
理解 Shell 脚本在自动化文件处理中的应用价值。

2. 实验内容
学习内容：简述通过 shell script.pdf 学习的 Shell 基础（如变量、循环、文件操作命令等）；
脚本设计：
明确遍历规则：遍历 ./test_folder 文件夹下的所有文件；
明确重命名规则：给所有文件添加前缀 new_；
脚本代码：完整粘贴上述 rename_files.sh 代码，并添加关键注释说明；
执行步骤：详细说明 “创建测试文件→赋予脚本权限→运行脚本” 的操作流程。


3. 实验结果
   (1)定义变量和获取变量
5. <img width="433" height="78" alt="image" src="https://github.com/user-attachments/assets/faa3a11e-11ac-4271-a289-005546760ed3" />
(2)使用数组
<img width="442" height="56" alt="image" src="https://github.com/user-attachments/assets/8e00e94d-054e-490b-8a25-eb260dff45fe" />
<img width="357" height="175" alt="image" src="https://github.com/user-attachments/assets/d9a2c98c-2423-4a5a-8e7d-8589e773b65c" />

（3）基本的操作符

（4）脚本决定制定 
（5）for循环
<img width="445" height="169" alt="image" src="https://github.com/user-attachments/assets/1eef9192-9a36-40cc-bdb5-03dc0c345d38" />

（6）output redirection
<img width="467" height="145" alt="image" src="https://github.com/user-attachments/assets/45929cd6-bbe1-4e76-9b25-fc6f9b859848" />



执行前文件列表：截图或文字说明 test_folder 初始文件（如 file1.txt file2.jpg file3.pdf）；
执行后文件列表：截图或文字说明重命名结果（如 new_file1.txt new_file2.jpg new_file3.pdf）；
脚本输出：终端执行脚本时的输出（如 重命名：file1.txt → new_file1.txt 等提示）；
结论：总结脚本是否达到预期功能，分析 Shell 脚本在批量文件处理中的优势。



