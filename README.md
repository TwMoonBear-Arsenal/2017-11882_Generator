
# CVE-2017-11882漏洞

A remote code execution vulnerability exists in Microsoft Office software when the software fails to properly handle objects in memory. An attacker who successfully exploited the vulnerability could run arbitrary code in the context of the current user.


# 關於本工具

* 可產生單一RTF檔案，用以驗證漏洞。

* 引用來源: [BlackMathIT](https://github.com/BlackMathIT/2017-11882_Generator)

* 修改原Python2語法為Python3可用。

## 使用方式

* python 2017-11882_Generator.py -x command_to_execute -o output_file_name

* Example:
python 2017-11882_Generator.py -x "cmd /c calc" -o test.rtf

## 免責聲明

本工具僅供研究使用
