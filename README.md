# Important Syntax of Markdown for Github
**bold**
***Italic***
>Nothing matters

one|two|three
-|-|-|
Four|Five|Six

``` Java
    public void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
    }

    @Override
    public View onCreateView(final LayoutInflater inflater, ViewGroup container,
                             Bundle savedInstanceState) {
        // Inflate the layout for this fragment
        View view = inflater.inflate(R.layout.fragment_one, container, false);

        Button button = (Button) view.findViewById(R.id.button);
        button.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                // do something
                MainActivity obj = new MainActivity();
                obj.trySwitch();
            }
        });
        return view;
        
    } 
```
***Italic***

*Italic Only*
## Using HTML and CSS
<p align="center">
<img src="https://www.google.com.np/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" width="400"/>
<img src="https://www.google.com.np/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" width="400"/>
</p>

# Using Markdown Syntax
![Remarkable Icon](https://www.google.com.np/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

* Hello
  * Hi
  
  https://www.youtube.com/
# Different Headres
  # This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

# Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## Inline Code
I think you should use an
`<addr>` element here instead.

# Auto Syntax Highlighting [four Space)
    def foo():
        if not bar:
            return True

## Checkbox 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Inline Html
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

## Horizontal Rule
---
Hyphens

***
Asterisks

___
Underscores
