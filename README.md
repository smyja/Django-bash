# Django-bash
This is a Bash script for setting up Django. Prefarably use a shortlink and curl to call the file. :)

Bitly shortlink is https://bit.ly/3zctaUI. Run `curl -L https://bit.ly/3zctaUI > s.sh` then `source s.sh`

### Running on Windows
Change the virtual environment from `/venv/bin/activate` to `venv/scripts/activate`

### Running it on MacOS
Mac OS X uses the BSD version of sed, which treats the -i option slightly differently. Instead, use [gsed](https://formulae.brew.sh/formula/gnu-sed) instead, install with `brew install gnu-sed`
then run `curl -L https://bit.ly/3n1AWJQ > a.sh` then `source a.sh`
