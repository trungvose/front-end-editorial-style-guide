# Front End Editorial Style Guide

A style guide on the standard format, spelling, and construction of commonly used words and phrases. For clarity and consistency of our internal and external communications – from our user interface to our sales, marketing, and commercial docs.

> This is our practical guide at [Zyllem][0]. Therefore, many of these standards are related to the logistic sector.

## Table of Contents

  - [Capitalization](#capitalization)
  - [Message Templates (Common Errors, Confirmations, etc.)](#message-templates-common-errors-confirmations-etc)
  - [Common Word Spellings](#common-word-spellings)
  - [Spelling and Formatting Rule](#spelling-and-formatting-rule)
    - [Spelling](#spelling)
    - [Numbers](#numbers)
    - [Date and time](#date-and-time)
    - [Units of measurement](#units-of-measurement)
      - [Time](#time)
      - [Distance](#distance)
    - [Commas](#commas)
  - [Common Grammar Dilemmas](#common-grammar-dilemmas)
    - [1. Plural Mishaps](#1-plural-mishaps)
    - [2. "&" versus "And"](#2-%22%22-versus-%22and%22)
    - [3. One word versus two words](#3-one-word-versus-two-words)
  - [Contributing](#contributing)

## Capitalization

<table>
    <tbody>
        <tr>
            <th align="left">Case</th>
            <th>Use In</th>
            <th>Examples</th>
            <th>Rules</th>
        </tr>
        <tr>
            <th align="left">Title Case</th>
            <td>
                <ul>
                    <li>Column Names (in tables)</li>
                    <li>Tab Names</li>
                    <li>Button Names</li>
                    <li>Menu Items</li>
                    <li>Clickable Elements (except if it is part of a sentence or error message)</li>
                </ul>
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/title-case.png" />
            </td>
            <td>
                <ol>
                    <li>Do capitalize major words<br>(e.g., <strong>Digitize Your Logistics</strong>)</li>
                    <li>Do capitalize first and last word<br>(e.g., <strong>Ordered On</strong>)</li>
                    <li>Do not capitalize minor words except if #2 is true<br>(e.g., <strong>Ordered on Network</strong>)</li>
                </ol>
            </td>
        </tr>
        <tr>
            <th align="left">Sentence case</th>
            <td>
                <ul>
                    <li>Check boxes</li>
                    <li>Radio buttons</li>
                    <li>Text box / field labels</li>
                    <li>Dialogs and instructions</li>
                    <li>Descriptions</li>
                    <li>Notifications&nbsp;</li>
                </ul>
            </td>
            <td>
              <img src="https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/sentence-case.png" />
            </td>
            <td>
                <ol>
                    <li>Do capitalize the first word only except if #2 is true.</li>
                    <li>Do capitalize proper nouns (names of people, technology, etc.)</li>
                </ol>
            </td>
        </tr>
        <tr>
            <th align="left">ALL CAPS</th>
            <td>
                <ul>
                    <li>SECTION HEADERS</li>
                </ul>
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/all-caps.png" />
            </td>
            <td></td>
        </tr>
    </tbody>
</table>

**[⬆ back to top](#table-of-contents)**

## Message Templates (Common Errors, Confirmations, etc.)

> Standard templates for some common messages

<table>
    <tbody>
        <tr>
            <th align="left">
                Case
            </th>
            <th>
                Template
            </th>
            <th>
                Example
            </th>
        </tr>
        <tr>
            <td>
                <strong>Forms:</strong> Field is blank
            </td>
            <td>
                <ul>
                    <li>FieldName is required.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Phone number is required.</li>
                    <li>Email address is required.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Forms:</strong> Wrong text format / value</td>
            <td>
                <ul>
                    <li>Please enter the FieldName in format: XXX.</li>
                    <li>Please enter a valid FieldName.</li>
                    <li>Please enter a unique FieldName.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Please enter the email address in format: <a>your@email.com</a></li>
                    <li>Please enter a valid Postal code.</li>
                    <li>Please enter a unique Code.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>
                <strong>Forms:</strong> Wrong numeric format / value
            </td>
            <td>
                <ul>
                    <li>Please enter a value between X and Y.</li>
                    <li>Please enter a &lt;adjective(s)&gt; number.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Please enter a value between 0 and 100.</li>
                    <li>Please enter a positive whole number.</li>
                    <li>Please enter a unique number.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Error messages and warnings</strong></td>
            <td>
                Message must contain at least 2 of the following in order:
                <ol>
                    <li>Problem</li>
                    <li>Cause/Effect of problem</li>
                    <li>Solution (with link if applicable)</li>
                </ol>
            </td>
            <td>
                <ul>
                    <li>Unable delete Warehouse1 because it is used by another resource.</span></li>
                    <li>
                        ‘Operator1’ does not have a team with a ‘Driver’ role. This will result in <u>Sync Issues</u>. Please <u>create or edit a team</u>.</span>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Action completed</strong></td>
            <td>
                <ul>
                    <li>The X has been &lt;action in past tense&gt;.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><span>The team has been added.</span></li>
                    <li><span>The contact has been updated.</span></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Confirm user-defined action</strong></td>
            <td>
                <ul>
                    <li>Are you sure you want to X? This action cannot be undone.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Are you sure you want to Cancel? This action cannot be undone.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Confirm deletion</strong></td>
            <td>
                <ul>
                    <li>Are you sure you want to delete X? This cannot cannot be undone.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Are you sure you want to delete Driver 1? This action cannot be undone.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Value already exists</strong></td>
            <td>
                <ul>
                    <li>'XXX' already exists. Please enter a unique &lt;PropertyName&gt;.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>'CUSTOMER_SURVEY' already exists. Please enter a unique code name.</li>
                    <li>'TEMP_ID' already exists. Please enter a unique ID.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>An element has been updated/deleted</strong></td>
            <td>
                <ul>
                    <li>This &lt;element&gt; has been updated or no longer exists.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>
                        This phone number has been updated or no longer exists.
                    </li>
                    <li>
                        This email has been updated or no longer exists.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Attempting to delete a primary element</strong></td>            
            <td>
                <ul>
                    <li>You cannot delete &lt;a primary resource&gt;.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>You cannot delete a primary email.</li>
                    <li>You cannot delete a primary phone number.</li>
                </ul>
                <br>
            </td>
        </tr>
        <tr>
            <td><strong>Action no longer valid</strong></td>
            <td>
                <ul>
                    <li>This action is no longer valid to X/Y items. Please refresh the page and try again.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>This action is no longer valid to 20/100 items. Please refresh the page and try again.</li>
                </ul>                        
            </td>
        </tr>
        <tr>
            <td><strong>Missing configuration</strong></td>
            <td>
                <ul>
                    <li>There are no X defined on this X.</li>
                    <li>This feature requires a X. Please add a X.</li>
                    <li>X is not enabled in your portal. Please &lt;instructions to solution&gt;.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>There are no users defined on this network.</li>
                    <li>This feature requires an operator. Please <u>add an operator</u>.</li>
                    <li>Support is not enabled in your portal. Please contact your administrator.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>Pre-requisite configuration</strong></td>
            <td>
                <ul>
                    <li>This feature requires XXX. Please <u>do this setting</u> and try again.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>
                        This feature requires a default currency. Please <u>set your currency</u> and try again.
                    </li>
                    <li>We noticed your file contains COD data. This feature requires a default currency. Please <u>set your currency</u> and try again.</li>
                </ul>
            </td>
        </tr>        
    </tbody>
</table>

**[⬆ back to top](#table-of-contents)**

## Common Word Spellings

The spellings are based on:

1. Most widely used spelling - references [Google Ngram (books)][1], [Thesaurus][2] and [Dictionary][3].
2. Avoid two words - combine words as first rule (e.g., **geolocation**). Otherwise, use dash if it makes more sense (e.g., **cloud-based**). This is a wide practice especially in the tech world.
3. Your own terminology - for words that are not in any official guide or publication, you should create our own standard. Note that others may spell them differently and that's okay. Consistency is the key.


<table>
    <tbody>
        <tr>
            <th align="left">
                Use This
            </th>
            <td><strong>Not This</strong></td>
            <td><strong>Comments</strong></td>
        </tr>
        <tr>
            <th align="left"><strong>geofencing</strong></th>
            <td>geo fencing, geo-fencing</td>
            <td>most compound words that start with <strong>geo </strong>are combined without a dash</td>
        </tr>
        <tr>
            <th align="left">geolocation</th>
            <td>geo location, geo-location, geo position</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">geozone</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">
                <p>photosign / photosignature</p>
            </th>
            <td>photoSign, photo-sign, photo sign</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">reroute</th>
            <td>re-route, re route</td>
            <td>most words with the prefix <strong>re</strong> are combined without a dash</td>
        </tr>
        <tr>
            <th align="left">recalculate</th>
            <td>re-calculate </td>
            <td></td>
        </tr>
        <tr>
            <th align="left">redeliver</th>
            <td>re-deliver</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">reassign, reassignment</th>
            <td>re-assign, re-assignment</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">reoptimize</th>
            <td>re-optimize</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">mutilingual</th>
            <td></td>
            <td>most words with the prefix <strong>multi</strong> are combined without a dash</td>
        </tr>
        <tr>
            <th align="left">multicountry</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">multi-delivery</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">timestamp</th>
            <td>time stamp</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">cloud-based</th>
            <td></td>
            <td>most compound words with the suffix <strong>based</strong> are combined with a dash</td>
        </tr>
        <tr>
            <th align="left">role-based</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">transaction-based</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">auto-assign, auto-assignment</th>
            <td>auto assign, autoassignment</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">autobundling, autobundle</th>
            <td>auto-bundling, auto-bundle, auto bundle</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">on-premise</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">cross-border</th>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th align="left">in-app</th>
            <td>inapp</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">real-time</th>
            <td>realtime</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">synchronize</th>
            <td>synchronise</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">sync, synced, syncs</th>
            <td>synch, synched, synchs</td>
            <td>
                <p>(This is not an American vs British spelling thing).</p>
                <p>Although the past tense <em>synched</em> is more widely used than <em>synced</em>, the present tenses: <strong>sync</strong> and <strong>syncs </strong>are more widely used especially in computing (and the usage gap is so much wider). So for consistency and to save space, we will get rid of the "<em>h"</em>.</p>
            </td>
        </tr>
        <tr>
            <th align="left">endpoint</th>
            <td>end-point</td>
            <td></td>
        </tr>       
        <tr>
            <th align="left">email</th>
            <td>e-mail</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">SMS</th>
            <td>sms</td>
            <td></td>
        </tr>
         <tr>
            <th align="left">Google Maps</th>
            <td>Google maps, google maps</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">iOS</th>
            <td>IOS, ios</td>
            <td></td>
        </tr>
        <tr>
            <th align="left">Android</th>
            <td>android</td>
            <td></td>
        </tr>        
    </tbody>
</table>

**[⬆ back to top](#table-of-contents)**

## Spelling and Formatting Rule

### Spelling

| Use This                                                                   | Not This                             | Comment                                                             |
| -------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------------------------------- |
| Use American English instead of British English (e.g., customize, fulfill) | customise, artefacts, fulfil, synced | We go for what is more widely used worldwide. [See this example][4] |

### Numbers

**Use this**

- Spell out if it's less than 10, use numeric if it's more than 10 (e.g., three, 25)
- Spell out when used as a compound adjective (fifty-thousand-foot view)

**Not this**

3 layers, twenty-five drivers

50-thousand-foot view

### Date and time

**Use this**

- Date
- Time
- Date and time

**Not this**

- date
- time
- Date and Time

### Units of measurement

These abbreviations must be used in both plural and singular forms.

For consistency and due to space constraints in the mobile app, let's NOT put a space between the number and the unit.

#### Time

| Use This                                                             | Not This             |
| -------------------------------------------------------------------- | -------------------- |
| Days, hours, minutes, seconds: d, h, min, s (e.g., 4d, 2h, 8min, 5s) | 4 d, 2 h, 8 min, 5 s |
| 6AM, 3PM                                                             | 6am, 6Am, 3Pm, 3pm   |

#### Distance

| Use This                                    | Not This     |
| ------------------------------------------- | ------------ |
| Kilometers, meter: km, m (e.g., 34km, 500m) | 34 km, 500 m |

### Commas

| Use This                                                                                    | Not This                         | Comment                                                                                   |
| ------------------------------------------------------------------------------------------- | -------------------------------- | ----------------------------------------------------------------------------------------- |
| Use serial comma (e.g., distance, traffic, and capacity). Notice the comma after "traffic". | Enterprise, network and operator | A must in contracts and legal documents. [Here's one of the many reasons][5] |

**[⬆ back to top](#table-of-contents)**

## Common Grammar Dilemmas

### 1. Plural Mishaps

| Use this        | Not this         |
| --------------- | ---------------- |
| Driver Name     | Drivers Name     |
| Customer Survey | Customers Survey |
| Item Summary    | Items Summary    |

### 2. "&" versus "And"

| & = united                                                                                                                                            | And = separated                                                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Search & select <br /> Both actions were performed as one like when you use a barcode scanner to scan barcode and the item was selected automatically | Search and select <br /> Search for the item and then tap to select the check box |
| Cookies & Cream <br /> ![Cookie & Cream][8]                                                                                                           | Cookies and Cream <br /> ![Cookie and Cream][9]                                   |
| Fruit & Nut <br /> ![Fruit & Nut][6]                                                                                                                  | Fruit and Nut <br /> ![Fruit & Nut][7]                                            |

### 3. One word versus two words

| One word = noun                  | Two words = verb             |
| -------------------------------- | ---------------------------- |
| What is your **login** password? | **Log in** with your account |
| The **pickup** time is at 3PM    | **Pick up** the parcel       |

**[⬆ back to top](#table-of-contents)**

## Contributing

I know this collection of standards is not perfect and still needs to improve. If you have any ideas, just [open an issue][issues] and tell me what you think.

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.


[0]: http://zyllem.com/
[1]: https://books.google.com/ngrams/graph?content=B2B%2CB+to+B&year_start=1800&year_end=2000&corpus=15&smoothing=5&share=&direct_url=t1%3B%2CB2B%3B%2Cc0%3B.t1%3B%2CB%20to%20B%3B%2Cc0
[2]: https://www.thesaurus.com/
[3]: https://www.dictionary.com/
[4]: https://books.google.com/ngrams/graph?content=customize%2C+customise&amp;year_start=1800&amp;year_end=2000&amp;corpus=15&amp;smoothing=5&amp;share=&amp;direct_url=t1%3B%2Ccustomize%3B%2Cc0%3B.t1%3B%2Ccustomise%3B%2Cc0
[5]: https://www.quickanddirtytips.com/education/grammar/the-10-million-comma
[6]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/fruit-nut.webp
[7]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/fruit-and-nut.webp
[8]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/cookie-cream.webp
[9]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/cookie-and-cream.webp
[10]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/title-case.png
[11]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/sentence-case.png
[12]: https://raw.githubusercontent.com/trungk18/front-end-editorial-style-guide/master/assets/images/all-caps.png
[issues]: https://github.com/trungk18/front-end-editorial-style-guide/issues/new
