Testing_process_BadBatch.md

1.commit to production github which is automatically updated and deployed via heroku
2. Check error logs for app crashing
3. Check for syntax error first. Set literal(static) values to variables to test syntax of code.
3.5 See if code on github.com shows you were the error is.
4. commit and check deployment logs
5. if error still persists c/p code in closure compiler. this will help identify compiler errors(syntax, parse, any formatting errors or sometimes semantic errors)
6. recommit and push