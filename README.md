# FourteenFish Zendesk theme

## Using SASS

In order to use SASS for development, you just need to compile it into the CSS that Zendesk Guide understands.
Note: Zendesk App Tools [theme preview](#publishing-your-theme) currently does not support live SASS compilation.

- Install Ruby, we use `sassc` gem to compile our `.scss` files. You can see how to install Ruby [here](https://www.ruby-lang.org/en/documentation/installation/).
- Install `sassc` gem. You can run:

```
    gem install sassc
```

Now you can compile your SASS files running:

```
./bin/compile.rb
```

Which will take all the `scss` files inside the `styles/` folder and create the `style.css` file that is consumable by Zendesk Guide.

## Publishing

Be sure to increment the version number in the `manifest.json` file before pushing to Git.
