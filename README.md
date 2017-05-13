# CustomProgressBar
Swift based custom progress bar

# How to use it
        var pgBar = CustomProgressBar(width: 200, height: 10)
        pgBar.configure()
        pgBar.progress(incremented: 190)
        
Add the `pgBar` wherever you like, it will be positioned at `x=0` and `y=0` of the parent view.

An example project using CustomProgressBar: https://github.com/utkarsh2012/ProgressBarTest

# Screenshot

<img width="240" alt="screen shot 2017-05-10 at 3 08 43 pm" src="https://cloud.githubusercontent.com/assets/137799/25924170/3285c1f4-3596-11e7-9fd1-57d6d3d1730c.png">
