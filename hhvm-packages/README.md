# Facebook - HHVM FastCGI

**- Container run**

    root@ruo91:~# docker run -d --name="hhvm" -p 9000:9000 -v /tmp:/tmp -v /home:/home ruo91/hhvm:packages
