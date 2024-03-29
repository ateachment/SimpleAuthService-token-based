# SimpleAuthService
<p>Development of a Simple Web Token (SWT)-based web application with Flask for teaching purposes</p>

Supports login with 
<ul>
<li>User name and password</li>
</ul>

Includes:
<ul>
<li>simple UI</li>
<li>authentification web service</li>
<li>pytest file</li>
<li>OpenAPI description file</li>
<li>MySql init file</li>
</ul>

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install -r requirements.txt
```
<p>Start MySQL/MariaDB server and run SQL script <i>initdb.sql</i></p>
<p>Copy or rename <i>settings-template.py</i> to <i>settings.py</i> and enter the appropriate connection data for the database (can be taken from <i>initdb.sql</i>).</p>

## Program start

```bash
python simpleAuthService.py
```

Open http://127.0.0.1:5000 with the browser.

## Testing

Start the test program with 
```bash
pytest testSimpleAuthService.py
```
and/or <br>
open <i>openapi.yaml</i> in https://editor.swagger.io/ and test the web service with the Swagger editor.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
