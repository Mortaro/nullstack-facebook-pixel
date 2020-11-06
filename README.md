
# Nullstack Facebook Pixel

Nullstack wrapper for [Facebook's Pixel](https://developers.facebook.com/docs/facebook-pixel)

## Install

```bash
npm install --save nullstack-facebook-pixel
```

## Usage

All you have to do is import and render the Facebook Pixel tag with your project ID as an attribute

This component will listen for Nullstack route changes and track a PageView

```jsx
import Nullstack from 'nullstack';
import FacebookPixel from 'nullstack-facebook-pixel';

class Application extends Nullstack {

  render() {
    return (
      <main>
        {/* your routes go here */}
        <FacebookPixel id="REPLACE_WITH_YOUR_FACEBOOK_PIXEL_ID" />
      </main>
    )
  }

}

export default Application;
```

## License

Nullstack Facebook Pixel is released under the [MIT License](https://opensource.org/licenses/MIT).