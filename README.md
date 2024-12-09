
# Debloat Windows 11

| :warning: Deprication WARNING |
|:----------------------------|
| > deprecated. Please use [rufus](https://github.com/pbatard/rufus) & [winutil](https://github.com/christitustech/winutil) |

Debloat your windows 11 install with ease.
Still work in progress. Some features might be missing.

## Change Executionpolicy

Open PowerShell with elevated permissions.

```powershell
Set-ExecutionPolicy Unrestricted
```

Select `A` for all.

## Clone the repo

```Powershell
git clone https://github.com/marsuper33/debloat-windows11.git

```


## Run

- Right click on the debloat.ps1 and select `run with powershell`.
- Accept the UAC prompt.
- click on the features/bloat you would like to remove or add.

## Feedback/Support

If you have any feedback or need help, please open an issue on the repo.

## Acknowledgements

This is based on windows10debloater by kdpuvvadi.

- [Windows11Debloater](https://github.com/kdpuvvadi/debloat-windows1)

## License

[MIT](https://choosealicense.com/licenses/mit/)
