`pip install flask extract-msg Pillow beautifulsoup4`
(Oder beliebiger python pkg manager, z.B. rye)


`python src/main.py`


`curl -X POST -F "file=@path/to/your/email-file.msg" http://localhost:8083/converter --output output.jpg`
