# alma-portfolio-url-update
Async python code that can be used to remove proxy strings embedded in portfolio url fields in Ex Libris Alma electronic portfolios.


Requires a spreadsheet containing the Portfolio Id, Collection Id, and Service Id of every portfolio you want to change. You will need to type the full name of the file.

Also, you will need to enter the string you wish to replace (your existing proxy string) with the desired replacement in the following line of code:
```data['linking_details']['static_url'] = data['linking_details']['static_url'].replace('', '') ('string to replace', 'new string. leave blank if you just want to delete') ```
