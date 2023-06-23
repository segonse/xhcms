# xhcms
vul_description

Through source code analysis, the downloads function is realized by cid and links taken out of the database on the downloads page. As long as the administrator cookie is obtained or csrf is used, the path of sensitive files written when the administrator publishes the download can be directly exploited, thus causing any file download vulnerability.
# Administrator account password:admin/admin,You can also use the broken access control vulnerability of the cms to directly log in to the management interface(https://github.com/Peanuts-s/XHcms)

The file link is the system file path.
![image](https://github.com/segonse/xhcms/assets/129601241/e9fc272a-0174-44e2-895a-4575782f7231)
![image](https://github.com/segonse/xhcms/assets/129601241/e1043589-edcc-4efc-b0e9-19eba0e5d1ae)

Click in turn to download the files
![image](https://github.com/segonse/xhcms/assets/129601241/b88b4cc7-273c-4faf-9772-7764a764b230)
![image](https://github.com/segonse/xhcms/assets/129601241/e08615c7-933f-44bf-979b-0311e501b4f3)
![image](https://github.com/segonse/xhcms/assets/129601241/91f0bdb3-87e7-48fb-85f1-98452da13530)
![image](https://github.com/segonse/xhcms/assets/129601241/71b74a6b-a0bb-412b-a134-f1af2b55ae2b)


