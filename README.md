# vscode-php-snippets
PHP snippets to help you be more productive when developing in PHP

## Note
### **This is a major work in progress that...*I've just started.* **

If you have a snippet that you use a lot submit a pull-request!

An issue would also be an easy way to suggest a snippet to be added.

Just add the code that you'd want to be turned in to a snippet and I'll see if I can't get it added.

## Current snippets
| Snippet       | Output                         |
|---------------|--------------------------------|
| `$_`          | `$_COOKIE['...']`              |
| `$_`          | `$_ENV['...']`                 |
| `$_`          | `$_FILES['...']`               |
| `$_`          | `$_GET['...']`                 |
| `$_`          | `$_POST['...']`                |
| `$_`          | `$_REQUEST['...']`             |
| `$_`          | `$_SERVER['...']`              |
| `$_`          | `$_SESSION['...']`             |
| `r`           | `return;`                      |
| `dd`          | `dd(...)`                      |
| `trt`         | `trait ... {`                  |
| `?=`          | `<?= ... ?>`                   |
| `c`           | `class ... {`                  |
| `cc`          | `class ... {` *w/ constuctor*  |
| `pfunc`       | `public function ...(...){...}`|

*As much as possible I try and make the ... be where your cursor ends up.*

## Known issues
I've not found a way to start a snippet with the leading less than symbol (`<...`). VS Code also seems to use the opening PHP tag to define it's context insead of the selector in the bottom right of the window (or the extension). So far I've not been able to add a snippet that would twig out an entire script yet.

-Jared