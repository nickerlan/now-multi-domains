**Dev mode**

now dev -A A.domain1.com.json (Works!)
now dev -A B.domain2.com.json (Works!)

**Deploy to A.domain1.com**

now -A A.domain1.com.json && now alias -A A.domain1.com.json 
(=> gives 404)

**Deploy to B.domain2.com**

now -A B.domain2.com.json && now alias -A B.domain2.com.json 
(=> gives 404)