#Placeholders scss

If you look for more speed and a css more small, you've to use placeholders

```css
%placeholder-n {
  property: value;
}
```

## Dependencies
- [Bourbon](http://bourbon.io/)

## Variables

```css
$color-primary : #03a9f4 !default;
$color-secondary : #009688 !default;
$color-black : #000 !default;
$color-white : #fff !default;
$font-size--base: 1em;
```

## Placeholders avaibles

###Text

- %font-size--base
- %font-weight--100
- %font-weight--200
- %font-weight--300
- %font-weight--400
- %font-weight--500

> The default **font-size: 1em**, you can change it with __*$font-size--base*__

### Blocks
- %display--block
- %display--flex
- %display--inline
- %display--inline-block
- %display--none
- %box-sizing--border-box

###Colors

- %color--white
- %color--black
- %color--primary
- %color--secondary

###Background
- %background-color--transparent
- %background-color--primary
- %background-color--secondary
- %background-color--white
- %background-color--black
- %background-repeat--repeat
- %background-repeat--no-repeat
- %background-size--cover
