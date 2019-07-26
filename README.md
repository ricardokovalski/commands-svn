# Script Commands SVN

## Incluir arquivos no trunk

```
$ svn add trunk/*
```

## Editando arquivos existentes no trunk

```
$ svn stat
```

## Tagging novas versões

```
$ svn cp trunk tags/{TAG}
```

## Fazendo commit

```
$ svn ci -m "comment" --username your_username --password your_password
```

## Deletando Tags

```
svn delete https://plugins.svn.wordpress.org/{PLUGIN}/tags/{TAG} -m "comment"
```
