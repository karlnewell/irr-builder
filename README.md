# Usage

Use python3 and virtualenv

```bash
python3 -m venv venv
source venv/bin/activate
```

Install python dependencies

```bash
pip install -r requirements.txt
```

Copy `input.yml.dist` to `input.yml` and update with your data  
Generate ARIN IRR templates

```bash
jinja2 arin.j2 input.yml
```
