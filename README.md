# today
Version 0.2.0

Add-on for todo.sh to show what is due today.

## Installing

```
cd ~/.todo.actions.d
git clone git@github.com:betsythefc/today.git
```

## Usage

```
$ date
Mon Jan  8 13:35:30 PST 2018
$ todo.sh list
(A) 2018-01-04 Clean @Apartment due:2018-01-08
(B) 2018-01-04 Finish homework
$ todo.sh today
(A) 2018-01-04 Clean @Apartment due:today
```
