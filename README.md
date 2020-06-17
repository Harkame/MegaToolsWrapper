# Megatools

(UNDER CONSTRUCTION)

Simple python Megatools wrapper

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/cc71191c41f141bf99265cb2f096370b)](https://www.codacy.com/manual/Harkame/MegaToolsWrapper?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Harkame/MegaToolsWrapper&amp;utm_campaign=Badge_Grade)
[![Maintainability](https://api.codeclimate.com/v1/badges/b54097b0e1de916a9e19/maintainability)](https://codeclimate.com/github/Harkame/MegaToolsWrapper/maintainability)

[Megatools](https://megatools.megous.com)

[Megatools (github)](https://github.com/megous/megatools)

## Installation

``` shell

pip install megatools

```

## Usage

### Initialization

``` python

from megatools import Megatools

megatools = Megatools() #Use megatools command in path

#OR

megatools = Megatools(executable="D:\\megatools\\megatools.exe")

```

### Get mega link filename

``` python

megatools.get_file_name("https://mega.nz/#!PpVB0CTZ!bwa51HbeKaVjuCff_lzbH4nQnV27uBxmcF89PnnACvY")

```

### dl - download exported files from mega.nz

``` python

megatools.dl("https://mega.nz/#!PpVB0CTZ!bwa51HbeKaVjuCff_lzbH4nQnV27uBxmcF89PnnACvY")

```

### Another commands incomming
