## InstallationForPackageParser

# Pycharm:

https://www.jetbrains.com/de-de/pycharm/download/#section=linux

herunterladen und entpacken
Zum Starten: bin/pycharm.sh öffnen

# pip installieren:

https://bootstrap.pypa.io/get-pip.py

get-pip.py herunterladen

python3.9 ~/Downloads/get-pip.py --user

oder ohne --user (jenachdem was klappt)

# Poetry installieren:

Hier bin ich mit nicht ganz sicher, wie ich es letztendlich geschafft habe:

Entweder:

curl -sSL https://install.python-poetry.org | python3.9 -

oder:

python3.9 -m pip install --user poetry

oder ohne --user

Bei mir ist poetry dann in ~/.poetry/bin/poetry . Das ggf. in Path einfügen

api-editor von Github clonen

cd api-editor/package-parser/

~/.poetry/bin/poetry install

Dann noch in IntelliJ das Environment hinzufügen. Das ist bei mir in:

~/.cache/pypoetry/virtualenvs/package-parser-_gm7iz2d-py3.9/bin/python3.9

Für die Test wird noch pytest benötigt:

~/.cache/pypoetry/virtualenvs/package-parser-_gm7iz2d-py3.9/bin/python3.9 -m pip install pytest

## API-Editor

npm herunterladen, entpacken und ./bin in PATH hinzufügen

(./gradlew build funktioniert gerade noch nicht)

cd gui/

npm install

und npm run dev

sollte aber schon funktionieren
