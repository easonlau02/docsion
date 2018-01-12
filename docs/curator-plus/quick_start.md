# Curator Plus
elasticsearch indices housekeeper, one curator instance housekeep all es instances' indices.

## Requirement

Maybe you have one elasticsearch instanse or more than one (I mean different cluster), here you need to setup one or more than one curator instance, which is not complated. if you have more and more instance, you need a all-in-one curator image like this.

## Getting Start

- Clone git folder

```bash
git clone https://github.com/easonlau02/curator-plus.git

```

- Create Action file

You need to change the action file under `action_file` folder, default file is to trim 14 days by age, you can use it for all instanse or create different yml file for every es instance.

