# as7

The attack I used was XSS.
1. you make a comment to the page of your attacker on WP 4.2 
2. Next you input this code <a title='x onmouseover=alert(unescape(/hello%20world/.source)) style=position:absolute;left:0;top:0;width:5000px;height:5000px  AAAAAAAAAAAA...[64 kb]..AAA'></a>
    64 kb worth of text in order for this to work 
3. Then as soon as the admin looks at the comment to review the following aleart shows 'Hello World' 
    - Screenshot under as XSS.jpeg

The Next one I did was finding out that a username exists
1. i tpe in a username then put in a random username to get me the results i need
    - screenshot under username.jpeg

The Last Exploit Is the password itself is the same as the username 
- Username: admin
- Password: admin
- screenshot acess 1 and 2