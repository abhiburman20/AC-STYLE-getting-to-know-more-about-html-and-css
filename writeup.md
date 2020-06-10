#CSS Resets :
We maynot get the output of what we actually desired. This may differ to different browsers. For example, if you tried your html page in different browser the css style will be differ with font-size, font-family, padding layout.This is because these valuse is set as default in different browser.
##CSS resets takes all the element and provides unified styles for all 
browser. It removes all the default sizing, margin, padding, and all 
the additional styles from the element.

### /* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
  */

  html, body, div, span, applet, object, iframe,
  h1, h2, h3, h4, h5, h6, p, blockquote, pre,
  a, abbr, acronym, address, big, cite, code,
  del, dfn, em, img, ins, kbd, q, s, samp,
  small, strike, strong, sub, sup, tt, var,
  b, u, i, center,
  dl, dt, dd, ol, ul, li,
  fieldset, form, label, legend,
  table, caption, tbody, tfoot, thead, tr, th, td,
  article, aside, canvas, details, embed,
  figure, figcaption, footer, header, hgroup,
  menu, nav, output, ruby, section, summary,
  time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
  }
  /* HTML5 display-role reset for older browsers */
  article, aside, details, figcaption, figure,
  footer, header, hgroup, menu, nav, section {
    display: block;
  }
  body {
    line-height: 1;
  }
  ol, ul {
    list-style: none;
  }
  blockquote, q {
    quotes: none;
  }
  blockquote:before, blockquote:after,
  q:before, q:after {
    content: '';
    content: none;
  }
  table {
    border-collapse: collapse;
    border-spacing: 0;
  }
  #The Cascading Rule
  ##Cascading allows to add different styles and overwrite the previous styles.
  In cascading whatever styles come at the bottom will have more precedence than the earlier one.
  ###p {
  background-color: orange;
  font-size: 24px;
}
p {
  background-color: green;
}
