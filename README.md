# Open Source Textbook

The Open Source Textbook is a my notes and lessons published on github for anyone. It is designed to be course agnostic, if you see an area not covered that you would like either leave an issue or if you're feeling more generous write it yourself and submit a pull request.

## Getting Started

To use this book, you just need to go to [main.pdf](main.pdf) and download. 

## Development 

In order to build the main text yourself you will need 

* LaTeX 
* Python 2 or 3

In order to use the *minted* package you will need the python packages `pygments` and `pygments-arm` installed. You can do this yourself or run the following cmds.

```
pip install pygments
git clone https://github.com/heia-fr/pygments-arm.git
cd pygments-arm
python setup.py install
cd ..\
rmdir pygments-arm
```

You will then be able to use your prefered LaTeX editor to edit and compile.

## Authors

* **Jacob Savage** - *Initial work* - [SaltySeaDog](https://github.com/SatlySeaDog)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the GPL v3.0 License - see the [LICENSE.md](LICENSE.md) file for details
