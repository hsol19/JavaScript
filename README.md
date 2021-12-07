# JavaScript
TIL about JavaScript


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript</title>
    <script src="js/example.js"></script>
    <script>
        /*
            javascript는 웹표준스크립트언어입니다.
        */

        document.write("반갑습니다.<br>");

        var box;
        box=100;
        var box1=100;
        box2=100;
        
        box=30;
        document.write(box+"<br>");

        document.write("<h1>Javascript</h1>");

        let t1="학교종이";
        let t2="땡땡땡";
        let t3="어서 모이자";

        document.write(t1+t2+t3+"<br>"); 

        var b=20;
        var f="20";
        document.write(b===f,"<br>");  
        document.write(b==f,"<br>");

        var a=10;
        var b=3;

        var result=a>b?"javascript":"hello";
        document.write(result+"<br>");

        var name=prompt("이름을 입력하세요","");
        document.write("입력한 이름 : "+name+"<br>");

        var num=3;
        if(num){
            document.write(num+"<br>");
        }

        var result = confirm("탈퇴하시겠습니까?");
        console.log(result); //개발자콘솔에 출력됨. 디버깅용
        if(result){
            document.write("탈퇴 처리됨");            
        }else{
            document.write("탈퇴 취소됨");
        }

        var id="easy1004";
        var pw="112233";

        var user_id=prompt("아이디는?","");
        var user_pw=prompt("비밀번호는?","");
        if(id==user_id){
            if(pw==user_pw){
                document.write(user_id+"님 반갑습니다.");
            }else{
                alert("비밀번호가 일치하지 않습니다.");
                location.reload();
            }
        } else{
            alert("아이디가 일치하지 않습니다.");
            location.reload();
        }

        var today=new Date();
        document.write(today.getFullYear()+"<br>");
        document.write((today.getMonth()+1)+"<br>");
        document.write(today.getDate()+"<br>");

    </script>

</head>
<body>
    환영합니다
</body>
</html>
