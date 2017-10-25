# テクノロジー（藤原）10/25授業

```
iso1:~/workspace $ [ ! -f ~/.ssh/id_rsa ] && ssh-keygen -t rsa
iso1:~/workspace $ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDX7Z3a+oWNJJo3UG2wPJo1Mk6NfyKmuYzJCpjiU39ZEs5i2FqZN1XYHAOlwi2baBt28PJrDUkkbFeFZAZGQuLCU4AQcSUvFUMM37mxdiiZz5VtKTjHQPs/aJ2XI0NNOQ6LaoykcRhoQlITQNcLiT8fK4QWLrElYkKr8dykn6jBjOleQOH9qp6NVS4aIcQbBNSibyrYTBxh1P707DtZwBjSqsAyuKJwNFKXDQcPTY+9RpqgU2YFg9jERqaHrZCgI6ecko8RBelSXNpCscYZ3ufDuWq1s4zBONf8+MUXh1daF10rVYpz62yBgIhc1V3ztZILgeJ1tdQ3rvoYsWxDhuMM470a6cmE7kZuuP4bRm0RvVQA7u01lgNFBkDnx2Pwug4uuwp/CJ29GWTEsiqsjQxiEefDjbxTqX0tR3ZZMvNsufRB4gDFjbifSjT7JmdQIPy9QuC2NmAsq9pWllaJkdcQ+2PLet6xkG0U9jUIPVCGsjbmF/fgroTpd5jKrzLtbVQ0BH9OvmP+0oEhxwBuOq8KBDaw6ZxEE/my9+sQRDHq9vDYdIsT66mBamn1KbCcigR63fIkkLD1mdtSXNjlbqKkmn2DsW3ggmIC12f/gQ0RA7X06hJWXzln9YGwzZzzQ9jNUvYMw+yJ5mHCQH1//I1HrDg5XXhEXWbaA3856qoNPw== kd1242983@st.kobedenshi.ac.jp
iso1:~/workspace $ ssh -T git@github.com
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
Hi iso-1! You've successfully authenticated, but GitHub does not provide shell access.
iso1:~/workspace $ git clone git@github.com:iso-1/lecture-1025.git
Cloning into 'lecture-1025'...
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
iso1:~/workspace $ git clone git@github.com:iso-1/project2-server-app.git
Cloning into 'project2-server-app'...
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
remote: Counting objects: 7, done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 7 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (7/7), done.
iso1:~/workspace $ pry
[1] pry(main)> puts "hello"
hello
=> nil
[2] pry(main)> print "hello"
hello=> nil
[3] pry(main)> p "hello"
"hello"
=> "hello"
[4] pry(main)> message = "hello"
=> "hello"
[5] pry(main)> puts message
hello
=> nil
[6] pry(main)> num = 123
=> 123
[7] pry(main)> puts num
123
=> nil
[8] pry(main)> puts message.length
5
=> nil
[9] pry(main)> 1234
=> 1234
[10] pry(main)> 1234.class
=> Integer
[11] pry(main)> 3.14159
=> 3.14159
[12] pry(main)> (3.14a159.class
[12] pry(main)*   (3.14159).class                        
[12] pry(main)*   Math::PI
[12] pry(main)*   3.14159.class                          
[12] pry(main)*   3.14.class                             
[12] pry(main)*   3.14.class                             
[12] pry(main)*   allfa
[12] pry(main)*   ls
self.methods: inspect  to_s
locals: 
  _   _dir_  _file_  _out_  message
  __  _ex_   _in_    _pry_  num    
[12] pry(main)*   ok
[12] pry(main)*   
```