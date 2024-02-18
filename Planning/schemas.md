# Schemas

## User

```python
{
userid : int,
name: str,
password : str 
}
```

## Tournament

```python
{
tournamentId: int,
hostId: int | userid, 
size: int
}
```

## Round

```python
{
roundId: int,
tournamentId: int | tournamentID,
teams: bool,
roundNum: int,
teamId : int || None,
userId : int || None
}
```

## Team

```python
{
teamId: int,
hostId: int | userid,
size: int
}
```
