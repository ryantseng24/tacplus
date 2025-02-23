# tacplus

因為測試BIGIP 與TACACS+ 整合，找到tacplus 的容器版本來用

容器啟用指令，tac_plus.conf 要先寫好

sudo docker run -td --name tacplus -p 49:49 -e DEBUGLEVEL=32         -v $dirconfigtacplus/tac_plus.conf:/etc/tacacs+/tac_plus.conf        llima3000/tacplus:latest
