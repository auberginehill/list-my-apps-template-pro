<!-- Visual Studio Code: For a more comfortable reading experience, use the key combination Ctrl + Shift + V

  _____           
 |  __ \          
 | |__) | __ ___  
 |  ___/ '__/ _ \ 
 | |   | | | (_) |
 |_|   |_|  \___/                                                                                        -->



## List My Apps Template - Pro

<table>
   <tr>
        <td style="padding:6px"><strong>OS:</strong></td>
        <td style="padding:6px">Android</td>
   </tr>
   <tr>
        <td style="padding:6px"><strong>Type:</strong></td>
        <td style="padding:6px">A template for an Android app called '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>'</td>
   </tr>
   <tr>
        <td style="padding:6px"><strong>Language:</strong></td>
        <td style="padding:6px">mostly HTML (with extra variables)</td>
   </tr>
   <tr>
        <td style="padding:6px"><strong>Description:</strong></td>
        <td style="padding:6px">This template (when run in an Android app called 'List My Apps') creates a HTML list (in list format) of the apps installed on the device.</td>
   </tr>
   <tr>
        <td style="padding:6px"><strong>Homepage:</strong></td>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro">https://github.com/auberginehill/list-my-apps-template-pro</a></td>
   </tr>
   <tr>
        <td style="padding:6px"><strong>Version:</strong></td>
        <td style="padding:6px">1.4</td>
   </tr>
   <tr>
        <td style="padding:6px"><strong>Sources:</strong></td>
        <td style="padding:6px">
            <table>
                <tr>
                    <td style="padding:6px">Emojis:</td>
                    <td style="padding:6px"><a href="https://api.github.com/emojis">https://api.github.com/emojis</a></td>
                </tr>
            </table>
        </td>
   </tr> 
   <tr>
        <td style="padding:6px"><strong>Downloads:</strong></td>
        <td style="padding:6px">For instance <a href="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-pro/master/all_in_one.txt">all_in_one.txt</a> or the same file in <a href="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-pro/master/file_header.txt">three</a> <a href="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-pro/master/body.txt">separate</a> <a href="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-pro/master/file_footer.txt">parts</a>. Or <a href="https://github.com/auberginehill/list-my-apps-template-pro/archive/master.zip">everything as a .zip-file</a>.</td>
   </tr>
</table>



#### Screenshot

<img class="screenshot" title="screenshot" alt="screenshot" height="70%" width="70%" src="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-pro/master/example_3.png">



#### Remarks

<table>
    <tr>
        <th>:warning:</th>
        <td style="padding:6px">
            <ul>
                <li>List My Apps custom templates consist of three fields ("List header", "Item format" and "List footer"). The template code in this project is divided into three parts, which correspond the fields found in List My Apps' Template Editor as described below:</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th></th>
        <td style="padding:6px">
            <ul>
                <ol>
                    <p>
                        <table>
                            <tr>
                                <td style="padding:6px"><strong>Filename</strong></td>
                                <td style="padding:6px"><strong>Field in List My Apps' Template Editor</strong></td>
                            </tr>
                            <tr>
                                <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/file_header.txt">file_header.txt</a></td>
                                <td style="padding:6px">"List header, may be blank"</td>
                            </tr>
                            <tr>
                                <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/body.txt">body.txt</a></td>
                                <td style="padding:6px">"Item format, may not be blank"</td>
                            </tr>
                            <tr>
                                <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/file_footer.txt">file_footer.txt</a></td>
                                <td style="padding:6px">"List footer, may be blank"</td>
                            </tr>
                            <tr>
                                <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/all_in_one.txt">all_in_one.txt</a></td>
                                <td style="padding:6px">Contains all the above mentioned three parts in one file.</td>
                            </tr>
                        </table>
                    </p>
                </ol>
                <p>
                    <li>After a HTML-file has been created, the template included in the bottom of that file is limited. If that limited template of the created HTML-file is to be used as a template in 'List My Apps' -app:
                        <ul>
                            <p>
                                <li>All instances of [dollar_sign] need to be changed with $</li>
                                <li>File Footer ends before [End Of Line].</li>
                            </p>
                        </ul>
                    </li>
                </p>
                <p>
                    <li>However, if the template code has been copied from this project [dollar_sign] strings should be left as they are.</li>
                </p>
            </ul>
        </td>
    </tr>
</table>



#### Tutorial

<table>
   <tr>
        <th>:book:</th>
        <td style="padding:6px">To open this code with an Android device, for instance:</td>
   </tr>
   <tr>
        <th></th>
        <td style="padding:6px">
            <ol>
                <p>
                    <li>Create a new template in '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>' -app's Template Editor by clicking Options (three dots) → Template Editor → Add. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-select-all.png">Screenshot</a>]</li>
                </p>
                <p>
                    <li>Type in a name for the template.<br><br>
                       <ol>
                          <img class="screenshot" title="screenshot" alt="screenshot" height="70%" width="70%" src="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-table/master/list_my_apps_-_template_editor.png">
                       </ol>
                    </li>
                </p>
                <p>
                    <li>Paste all the appropriate template data (the three sections as specified below) to 'List My Apps' and save the template.<br><br>
                        <ul>
                            <p>
                                <table>
                                    <tr>
                                        <td style="padding:6px"><strong>Filename</strong></td>
                                        <td style="padding:6px"><strong>Field in List My Apps' Template Editor</strong></td>
                                    </tr>
                                    <tr>
                                        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/file_header.txt">file_header.txt</a></td>
                                        <td style="padding:6px">"List header, may be blank"</td>
                                    </tr>
                                    <tr>
                                        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/body.txt">body.txt</a></td>
                                        <td style="padding:6px">"Item format, may not be blank"</td>
                                    </tr>
                                    <tr>
                                        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/file_footer.txt">file_footer.txt</a></td>
                                        <td style="padding:6px">"List footer, may be blank"</td>
                                    </tr>
                                    <tr>
                                        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/blob/master/all_in_one.txt">all_in_one.txt</a></td>
                                        <td style="padding:6px">Contains all the above mentioned three parts in one file.</td>
                                    </tr>
                                </table>
                            </p>
                        </ul>
                    </li>
                </p>
                <p>
                    <li>After saving the template go back to the 'List My Apps' -app's home screen and select the name that was created in Step 2 from the 'Copy/Share as:' -dropdown menu. Please also select the apps that you'd like to be included in the list. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-App-HTML-list.png">Screenshot</a>]</li>
                </p>
                <p>
                    <li>'Run' the 'List My Apps' -app with the new template by copying the app data to Clipboard [Copy] (since direct sharing may not work, if a lot of applications has been installed).
                        <ul>
                            <li>There seems to be some kind of a limit, how much data the Android Clipboard can contain. With verbose templates ~200 apps might be the upper limit, but with a simple template, the Android Clipboard clearly is capable of containing considerably more app data.</li>
                        </ul>
                    </li>
                </p>
                <p>
                    <li>Open a HTML editor, such as <a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a>.</li>
                </p>
                <p>
                    <li>Paste the app data (source code generated by 'List My Apps' in Step 5) from Clipboard to the HTML editor.
                        <ul>
                            <li>If nothing happens (no data is pasted to a HTML editor after a few seconds), try selecting fewer apps in 'List My Apps' and go back to Step 5.</li>
                                <ul>
                                    <li>Depending on the device some lagging may occur when trying to paste, say ~10000 lines of code.</li>
                                </ul>
                            <li>If "old data" gets pasted to a HTML editor (i.e. "the data that was in the Clipboard before List My Apps' 'Copy to Clipboard' -button was clicked"), try selecting fewer apps in 'List My Apps' and go back to Step 5.</li>
                        </ul>
                        </li>
                </p>
                <p>
                    <li>Save the file as a HTML file, for example as 'Installed_Apps.html', for example in 'Home/Documents' folder (a filename without any spaces is recommended).</li>
                </p>
                <p>
                    <li>Open the HTML-file with an appropriate app, such as a browser by surfing directly to the file location, which could, for instance, be: <a href="file:///storage/emulated/0/Documents/Installed_Apps.html">file:///storage/emulated/0/Documents/Installed_Apps.html</a>
                        <ul>
                            <li>In a browser the spaces in the filename can be replaced with %20 to make the link work. For more exotic filename characters, see <a href="http://www.w3schools.com/tags/ref_urlencode.asp">HTML URL Encoding Reference</a>.</li>
                        </ul>
                        </li>
                </p>
                <p>
                    <li>Conversion from HTML to PDF might work with <a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox (for Android)</a> (Options (three dots) → Page → Save as PDF) or perhaps with the printing option in the default Android File Manager.</li>
                </p>
            </ol>
        </td>
   </tr>
</table>

<ol>   
   <table>
      <tr>
        <th>:bulb:</th>
        <th>Tip:</th>
        <td style="padding:6px">To see the code (<a href="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-pro/master/all_in_one.html">all_in_one.html</a>) in action, a real-time Online HTML Editor can be found at: <a href="http://htmledit.squarefree.com/">http://htmledit.squarefree.com/</a></td>
      </tr>
   </table>
</ol>



#### Contributing

<p>Find a bug? Have a feature request? Here is how you can contribute to this project:</p>

 <table>
   <tr>
      <th><img class="emoji" title="contributing" alt="contributing" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f33f.png"></th>
      <td style="padding:6px"><strong>Bugs:</strong></td>
      <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/issues">Submit bugs</a> and help us verify fixes.</td>
   </tr> 
   <tr>
      <th rowspan="2"></th>
      <td style="padding:6px"><strong>Feature Requests:</strong></td>
      <td style="padding:6px">Feature request can be submitted by <a href="https://github.com/auberginehill/list-my-apps-template-pro/issues">creating an Issue</a>.</td>
   </tr> 
   <tr>
      <td style="padding:6px"><strong>Edit Source Files:</strong></td>
      <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro/pulls">Submit pull requests</a> for bug fixes and features and discuss existing proposals.</td>
   </tr>
 </table>   



#### www

<table>
    <tr>
        <th><img class="emoji" title="www" alt="www" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f310.png"></th>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-pro">Template Homepage</a></td>
    </tr>
    <tr>
        <th rowspan="12"></th>
        <td style="padding:6px"><a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a> (Google Play)</td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="http://www.onyxbits.de/listmyapps">List My Apps' homepage</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="http://forum.xda-developers.com/showthread.php?t=2460266">List My Apps' application thread</a> at xda-developers.com</td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a> (free code editor)</td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="https://play.google.com/store/apps/details?id=jp.ne.shira.html.viewer">Local HTML Viewer</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox for Android</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="https://play.google.com/store/apps/details?id=com.alorma.github">Gitskarios for Github</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="http://tmpvar.com/markdown.html">Github Markdown Previewer</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="http://htmlhint.com/">HTMLHint</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="https://text-compare.com/#">Text Compare</a></td>
    </tr>
    <tr>
        <td style="padding:6px"><a href="http://htmlescape.net/htmlescape_tool.html">Escape HTML Entities</a></td>
    </tr>
    <tr>
        <td style="padding:6px">ASCII Art: <a href="http://www.figlet.org/">http://www.figlet.org/</a> and <a href="http://www.network-science.de/ascii/">ASCII Art Text Generator</a></td>
    </tr>
</table>



#### Related scripts

 <table>
   <tr>
        <th><img class="emoji" title="www" alt="www" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/0023-20e3.png"></th>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-table">List My Apps Template - Table</a></td>
   </tr>
   <tr>
        <th rowspan="5"></th>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-list">List My Apps Template - List</a></td>
   </tr>
   <tr>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-data">List My Apps Template - Data</a></td>
   </tr>
   <tr>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain">List My Apps Template - XML plain</a></td>
   </tr>
   <tr>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-xml-style">List My Apps Template - XML style</a></td>
   </tr>
   <tr>
        <td style="padding:6px"><a href="https://github.com/auberginehill/list-my-apps-template-json">List My Apps Template - JSON</a></td>
   </tr>
</table>
