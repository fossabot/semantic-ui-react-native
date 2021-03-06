<p align="center">
  <img alt="semantic-ui-react-native" src="https://user-images.githubusercontent.com/4863567/102728950-86e3aa80-433f-11eb-9f6c-edbe1153a8b5.png" width="300">
</p>

<p align="center">
  React Native İçin Semantic Arayüz Paketi
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@muratoner/semantic-ui-react-native"><img src="https://img.shields.io/npm/v/@muratoner/semantic-ui-react-native.svg"></a>
  <a href="https://travis-ci.org/muratoner/semantic-ui-react-native"><img src="https://img.shields.io/travis/muratoner/semantic-ui-react-native/master.svg"></a>
  <a href="https://codecov.io/gh/muratoner/semantic-ui-react-native"><img src="https://codecov.io/gh/muratoner/semantic-ui-react-native/coverage.svg"></a>
  <a href="https://www.npmjs.com/package/@muratoner/semantic-ui-react-native"><img src="https://img.shields.io/npm/dm/@muratoner/semantic-ui-react-native.svg"></a>
  <a href="https://github.com/prettier/prettier"><img src="https://img.shields.io/badge/styled_with-prettier-ff69b4.svg"></a>
  <a href="http://makeapullrequest.com/"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
  <a href="https://david-dm.org/muratoner/semantic-ui-react-native"><img src="https://david-dm.org/muratoner/semantic-ui-react-native.svg"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
</p>

<p align="center">
  <img alt="semantic-ui-react-native" src="https://user-images.githubusercontent.com/4863567/102729025-e477f700-433f-11eb-8e5a-08b466c7c211.jpg">
</p>

## İlk Adım

### Kurulum

#### 1.Adım: @muratoner/semantic-ui-react-native paketini yükleyin

```bash
# yarn
yarn add @muratoner/semantic-ui-react-native
# veya npm ile
npm i @muratoner/semantic-ui-react-native --save
```

#### 2.Adım: react-native-vector-icons paketini yükleyin!

Eğer react-native-vector-icons paketi projenizde yüklü ise bu adımı geçebilirsiniz. Yüklü değilse alttaki adımları takip edin:

> Manual linking of react-native-vector-icons is not necessary if you're using react-native@0.60.0 or above since it is done automatically. This will throw an error though it won't prevent the application from running. To fix this you'll simply have to run react-native unlink react-native-vector-icons and the process will run as expected.

```bash
# yarn
yarn add react-native-vector-icons
# veya npm ile
npm i --save react-native-vector-icons

# link
react-native link react-native-vector-icons
```

Eğer react-native-vector-icons paket kurulumu ile igili sorun yaşıyorsanız, Buradaki adımları takip ederek sorunu giderebilirsiniz [here](https://github.com/oblador/react-native-vector-icons#installation).

### Örnek Kullanım

Paketi isterseniz Snack üzerinden rahatlıkla test edebilirsiniz
[here](https://snack.expo.io/@muratoner/semantic-ui-react-native).

```js
import { Button, LabeledButton } from '@muratoner/semantic-ui-react-native';

<Button
  disabled
  loading
  outline
  title="Add Friend"
  color="red"
  iconName="user"
  iconType="FontAwesome"
/>;
<LabeledButton
  outline
  pointing
  color="primary"
  label="Forks"
  labelIcon="fork"
  labelIconType="AntDesign"
  title="1,048"
/>;
```

## Hazır Bileşenler

- [ ] Accordion
- [ ] Avatar
- [ ] Badge
- [ ] BottomSheet
- [ ] Breadcrumb
- [x] Button
- [ ] ButtonGroup
- [ ] Card
- [ ] CheckBox
- [ ] Comment
- [ ] Divider
- [ ] Dimmer
- [ ] Feed
- [ ] Flag
- [ ] Grid
- [ ] Header
- [ ] HTML style headings
- [x] Icon
- [ ] Image
- [ ] Input
- [ ] Label
- [ ] ListItem
- [ ] Loader
- [ ] Message
- [ ] Overlay
- [ ] Placeholder
- [ ] Pricing
- [ ] Progress
- [ ] Rating
- [ ] SearchBar
- [ ] Segment
- [ ] Statistic
- [ ] Step
- [ ] Slider
- [ ] Social Icons / Social Icon Buttons
- [ ] Tab
- [ ] Table
- [ ] Tile
- [ ] Tooltip

