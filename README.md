# 🗣 Subject &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Libft

<br><br>
<table>
  <tr>
    <td>Program&nbsp;&nbsp;name</td>
    <td>libft.a</td>
  </tr>
  <tr>
    <td>Turn&nbsp;&nbsp;in&nbsp;&nbsp;files</td>
    <td>Makefile,&nbsp;&nbsp;libft.h,&nbsp;&nbsp;ft_*.c</td>
  </tr>
   <tr>
    <td>Makefile</td>
    <td>NAME,&nbsp;&nbsp;all,&nbsp;&nbsp;clean,&nbsp;&nbsp;fclean,&nbsp;&nbsp;re</td>
  </tr>
   <tr>
    <td>External&nbsp;&nbsp;functs</td>
    <td>Detailed&nbsp;&nbsp;below</td>
  </tr>
  <tr>
    <td>Libft&nbsp;&nbsp;authorized</td>
    <td>n/a</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Write&nbsp;&nbsp;your&nbsp;&nbsp;own&nbsp;&nbsp;library:&nbsp;&nbsp;a&nbsp;&nbsp;collection&nbsp;&nbsp;of&nbsp;&nbsp;functions&nbsp;&nbsp;that&nbsp;&nbsp;will&nbsp;&nbsp;be&nbsp;&nbsp;a&nbsp;&nbsp;useful&nbsp;&nbsp;tool&nbsp;&nbsp;for&nbsp;&nbsp;your cursus</td>
  </tr>
</table>
<br>
<p>
<h3>Technical considerations</h3>
<ul>
  <li>Declaring&nbsp;&nbsp;global&nbsp;&nbsp;variables&nbsp;&nbsp;is&nbsp;&nbsp;forbidden
  <li>If&nbsp;&nbsp;you&nbsp;&nbsp;need&nbsp;&nbsp;helper&nbsp;&nbsp;functions&nbsp;&nbsp;to&nbsp;&nbsp;split&nbsp;&nbsp;a&nbsp;&nbsp;more&nbsp;&nbsp;complex&nbsp;&nbsp;function,&nbsp;&nbsp;define&nbsp;&nbsp;theam&nbsp;&nbsp;as&nbsp;&nbsp;static&nbsp;&nbsp;functions.&nbsp;&nbsp;This&nbsp;&nbsp;way,&nbsp;&nbsp;their&nbsp;&nbsp;scope&nbsp;&nbsp;will&nbsp;&nbsp;be&nbsp;&nbsp; limited&nbsp;&nbsp;to&nbsp;&nbsp;the&nbsp;&nbsp;appropriate&nbsp;&nbsp;file
  <li>Place&nbsp;&nbsp;all&nbsp;&nbsp;your&nbsp;&nbsp;files&nbsp;&nbsp;at&nbsp;&nbsp;the&nbsp;&nbsp;root&nbsp;&nbsp;of&nbsp;&nbsp;your&nbsp;&nbsp;repository
  <li>Turning&nbsp;&nbsp;in&nbsp;&nbsp;unused&nbsp;&nbsp;files&nbsp;&nbsp;is&nbsp;&nbsp;forbidden
  <li>Every&nbsp;&nbsp;.c&nbsp;&nbsp;files&nbsp;&nbsp;must&nbsp;&nbsp;compile&nbsp;&nbsp;with&nbsp;&nbsp;the&nbsp;&nbsp;flags&nbsp;&nbsp;-Wall&nbsp;&nbsp;-Wextra&nbsp;&nbsp;-Werror
  <li>You&nbsp;&nbsp;must&nbsp;&nbsp;use&nbsp;&nbsp;the&nbsp;&nbsp;command&nbsp;&nbsp;ar&nbsp;&nbsp;to&nbsp;&nbsp;create&nbsp;&nbsp;your&nbsp;&nbsp;library.&nbsp;&nbsp;Using&nbsp;&nbsp;the&nbsp;&nbsp;libtool&nbsp;&nbsp;command&nbsp;&nbsp;is&nbsp;&nbsp;forbidden
  <li>Your&nbsp;&nbsp;libft.a&nbsp;&nbsp;has&nbsp;&nbsp;to&nbsp;&nbsp;be&nbsp;&nbsp;created&nbsp;&nbsp;at&nbsp;&nbsp;the&nbsp;&nbsp;root&nbsp;&nbsp;of&nbsp;&nbsp;your&nbsp;&nbsp;repository
</ul>
</p>
<br>
<p>
<h2>Part&nbsp;&nbsp;1&nbsp;&nbsp;-&nbsp;&nbsp;Libc&nbsp;&nbsp;functions</h2>
<p>
To&nbsp; begin, &nbsp;you&nbsp; must&nbsp; redo &nbsp;a &nbsp;set &nbsp;of &nbsp;functions &nbsp;from &nbsp;the &nbsp;libc. &nbsp;Your &nbsp;functions&nbsp; will&nbsp; have &nbsp;the &nbsp;same&nbsp; prototypes &nbsp;and &nbsp;implement &nbsp;the &nbsp;same &nbsp;behaviors&nbsp; as &nbsp;the &nbsp;originals. &nbsp;They&nbsp; must&nbsp; comply &nbsp;with &nbsp;the &nbsp;way &nbsp;they &nbsp;are &nbsp;defined &nbsp;in &nbsp;their &nbsp;<b>man</b>. &nbsp;The &nbsp;only &nbsp;difference &nbsp;will &nbsp;be &nbsp;their&nbsp; names. &nbsp;They &nbsp;will begin &nbsp;with &nbsp;the &nbsp;’ft_’ &nbsp;prefix.&nbsp; For &nbsp;instance, &nbsp;strlen &nbsp;becomes &nbsp;ft_strlen.
</p>
<p>
You &nbsp;must &nbsp;write &nbsp;your &nbsp;own &nbsp;function &nbsp;implementing &nbsp;the &nbsp;following &nbsp;original &nbsp;ones. &nbsp;They &nbsp;do &nbsp;not &nbsp;require &nbsp;any &nbsp;external &nbsp;functions:
</p>
</p>
<table>
<tr>
<td>isalpha</td>
<td>isdigit</td>
<td>isalnum</td>
<td>isascii</td>
<td>isprint</td>
<td>strlen</td>
<td>memset</td>
<td>bzero</td>
</tr>
<tr>
<td>memcpy</td>
<td>memmove</td>
<td>strlcpy</td>
<td>strlcat</td>
<td>memchr</td>
<td>memcmp</td>
<td>strnstr</td>
<td>atoi</td>
</tr>
<tr>
<td>strdup</td>
<td>calloc</td>
<td>toupper</td>
<td>tolower</td>
<td>strchr</td>
<td>strrchr</td>
<td>strncmp</td>
</tr>
</table>
<br>
<p>
<h2>Part &nbsp;2&nbsp; -&nbsp; Additional &nbsp;functions</h2>
</p>

<p>
In &nbsp;this &nbsp;second &nbsp;part,&nbsp; you &nbsp;must &nbsp;develop &nbsp;a &nbsp;set &nbsp;of &nbsp;functions&nbsp; that &nbsp;are &nbsp;either&nbsp; not &nbsp;in &nbsp;the &nbsp;libc, &nbsp;or&nbsp; that&nbsp; are &nbsp;part&nbsp; of &nbsp;it&nbsp; but&nbsp; in&nbsp; a&nbsp; different &nbsp;form.
</p>

<table>
  <tr>
    <td>Function &nbsp;name</td>
    <td>ft_substr</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>char&nbsp; *ft_substr(char&nbsp; const &nbsp;*s, unsigned &nbsp;int &nbsp;start, &nbsp;size_t &nbsp;len);</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in&nbsp; files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s: &nbsp;The &nbsp;string&nbsp; from &nbsp;which&nbsp; to &nbsp;create&nbsp; the &nbsp;substring.<br>start: &nbsp;The &nbsp;start &nbsp;index &nbsp;of &nbsp;the&nbsp; substring&nbsp; in&nbsp; the&nbsp; string &nbsp;’s’.<br>len:&nbsp; The&nbsp; maximum &nbsp;length&nbsp; of&nbsp; the &nbsp;substring.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>The &nbsp;substring.<br>NULL&nbsp; if &nbsp;the&nbsp; allocation&nbsp; fails.</td>
  </tr>
  <tr>
    <td>External&nbsp; functs. </td>
    <td>malloc</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Allocates &nbsp;(with&nbsp; malloc(3))&nbsp; and&nbsp; returns&nbsp; a&nbsp; substring&nbsp; from &nbsp;the &nbsp;string&nbsp; ’s’.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>The&nbsp; substring&nbsp; begins&nbsp; at&nbsp; index &nbsp;’start’&nbsp; and &nbsp;is &nbsp;of &nbsp;maximum&nbsp; size &nbsp;’len’.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_strjoin</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>char &nbsp;*ft_strjoin(char &nbsp;const &nbsp;*s1, &nbsp;char &nbsp;const &nbsp;*s2);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s1:&nbsp; The&nbsp; prefix &nbsp;string.<br>s2: &nbsp;The &nbsp;suffix &nbsp;string.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>The &nbsp;new &nbsp;string.<br>NULL &nbsp;if&nbsp; the &nbsp;allocation &nbsp;fails.</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Allocates &nbsp;(with &nbsp;malloc(3))&nbsp; and &nbsp;returns&nbsp; a &nbsp;new &nbsp;string,&nbsp; which &nbsp;is &nbsp;the&nbsp;&nbsp;of &nbsp;the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>concatenation&nbsp; of &nbsp;’s1’ &nbsp;and&nbsp; ’s2’.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_strtrim</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>char &nbsp;*ft_strtrim(char &nbsp;const &nbsp;*s1, &nbsp;char &nbsp;const &nbsp;*set);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s1: &nbsp;The &nbsp;string &nbsp;to &nbsp;be &nbsp;trimmed.<br>set:&nbsp; The &nbsp;reference &nbsp;set &nbsp;of &nbsp;characters &nbsp;to &nbsp;trim.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>The &nbsp;trimmed &nbsp;string.<br>NULL &nbsp;if &nbsp;the &nbsp;allocation &nbsp;fails.</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Allocates &nbsp;(with&nbsp; malloc(3))&nbsp; and&nbsp; returns &nbsp;a &nbsp;copy &nbsp;of &nbsp;’s1’&nbsp; with&nbsp; the &nbsp;characters&nbsp;specified&nbsp;<br>&nbsp;in &nbsp;’set’ &nbsp;removed &nbsp;from &nbsp;the&nbsp; beginning &nbsp;and &nbsp;the &nbsp;end &nbsp;of &nbsp;the &nbsp;string.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_split</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>char &nbsp;**ft_split(char &nbsp;const &nbsp;*s,&nbsp; char &nbsp;c);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s: &nbsp;The &nbsp;string &nbsp;to &nbsp;be &nbsp;split.<br>c:&nbsp; The &nbsp;delimiter&nbsp; character.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>The &nbsp;array&nbsp; of&nbsp; new&nbsp; strings &nbsp;resulting &nbsp;from &nbsp;the &nbsp;split.<br>NULL &nbsp;if &nbsp;the &nbsp;allocation &nbsp;fails.</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc, &nbsp;free</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Allocates &nbsp;(with &nbsp;malloc(3)) &nbsp;and &nbsp;returns &nbsp;an &nbsp;array &nbsp;of &nbsp;strings &nbsp;obtained &nbsp;by &nbsp;splitting ’s’ &nbsp;&nbsp;<br>using &nbsp;the &nbsp;character &nbsp;’c’ &nbsp;as &nbsp;a &nbsp;delimiter. &nbsp;The &nbsp;array&nbsp; must &nbsp;end&nbsp;&nbsp;with<br> &nbsp;a &nbsp;NULL &nbsp;pointer.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_itoa</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>char &nbsp;*ft_itoa(int &nbsp;n);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>n: &nbsp;the &nbsp;integer&nbsp; to &nbsp;convert.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>The &nbsp;string &nbsp;representing &nbsp;the &nbsp;integer.<br>NULL &nbsp;if &nbsp;the&nbsp; allocation&nbsp; fails.</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Allocates &nbsp;(with &nbsp;malloc(3)) &nbsp;and &nbsp;returns&nbsp; a&nbsp; string&nbsp; representing&nbsp; the&nbsp; integer&nbsp; received&nbsp; &nbsp;&nbsp;&nbsp;<br>as &nbsp;an &nbsp;argument. &nbsp;Negative &nbsp;numbers &nbsp;must&nbsp; be &nbsp;handled.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_strmapi</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>char &nbsp;*ft_strmapi(char&nbsp; const &nbsp;*s, &nbsp;char &nbsp;(*f)(unsigned &nbsp;int, &nbsp;char));</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s:&nbsp; The &nbsp;string &nbsp;on&nbsp; which&nbsp; to &nbsp;iterate.<br>f: &nbsp;The &nbsp;function &nbsp;to &nbsp;apply &nbsp;to &nbsp;each&nbsp; character.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>The &nbsp;string &nbsp;created &nbsp;from &nbsp;the &nbsp;successive &nbsp;applications<br>of ’f’.<br>Returns &nbsp;NULL &nbsp;if &nbsp;the&nbsp; allocation &nbsp;fails.</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Applies &nbsp;the &nbsp;function &nbsp;’f’ &nbsp;to &nbsp;each &nbsp;character &nbsp;of &nbsp;the &nbsp;string ’s’, &nbsp;and &nbsp;passing&nbsp; its&nbsp; index as<br>first argument&nbsp; to &nbsp;create &nbsp;a &nbsp;new &nbsp;string &nbsp;(with &nbsp;malloc(3))&nbsp;resulting &nbsp;from &nbsp;successive<br>applications &nbsp;of &nbsp;’f’.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_striteri</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_striteri(char &nbsp;*s, &nbsp;void &nbsp;(*f)(unsigned &nbsp;int, &nbsp;char*));</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s: &nbsp;The &nbsp;string &nbsp;on &nbsp;which &nbsp;to &nbsp;iterate.<br>f: &nbsp;The &nbsp;function &nbsp;to &nbsp;apply &nbsp;to &nbsp;each&nbsp; character.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Applies &nbsp;the &nbsp;function &nbsp;’f’ &nbsp;on &nbsp;each &nbsp;character &nbsp;of &nbsp;the&nbsp; string&nbsp; passed&nbsp; as&nbsp; argument,&nbsp; <br>passing &nbsp;its &nbsp;index &nbsp;as &nbsp;first &nbsp;argument.&nbsp; Each&nbsp; character &nbsp;is&nbsp; passed&nbsp; by &nbsp;address&nbsp; to&nbsp; ’f’ &nbsp;to&nbsp; <br>be &nbsp;modified &nbsp;if&nbsp; necessary.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_putchar_fd</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_putchar_fd(char &nbsp;c, &nbsp;int &nbsp;fd);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td> c:&nbsp; The&nbsp; character&nbsp; to &nbsp;output. &nbsp;<br>fd: &nbsp;The &nbsp;file &nbsp;descriptor &nbsp;on &nbsp;which &nbsp;to &nbsp;write.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>write</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Outputs &nbsp;the &nbsp;character &nbsp;’c’ &nbsp;to &nbsp;the &nbsp;given &nbsp;file &nbsp;descriptor.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_putstr_fd</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_putstr_fd(char &nbsp;*s, &nbsp;int &nbsp;fd);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s: &nbsp;The &nbsp;string &nbsp;to &nbsp;output. &nbsp;<br>fd: &nbsp;The &nbsp;file &nbsp;descriptor &nbsp;on &nbsp;which &nbsp;to&nbsp; write.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>write</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Outputs&nbsp; the &nbsp;string &nbsp;’s’ &nbsp;to&nbsp; the&nbsp; given &nbsp;file &nbsp;descriptor.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_putendl_fd</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_putendl_fd(char &nbsp;*s, &nbsp;int &nbsp;fd);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>s: &nbsp;The &nbsp;string &nbsp;to&nbsp; output. &nbsp;<br>fd:&nbsp; The &nbsp;file &nbsp;descriptor&nbsp; on &nbsp;which &nbsp;to &nbsp;write.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>write</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Outputs &nbsp;the &nbsp;string&nbsp; ’s’ &nbsp;to &nbsp;the &nbsp;given &nbsp;file&nbsp; descriptor &nbsp;followed&nbsp; by &nbsp;a &nbsp;newline.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_putnbr_fd</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_putnbr_fd(int &nbsp;n, &nbsp;int &nbsp;fd);</td>
  </tr>
  <tr>
    <td>Turn&nbsp; in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>n: &nbsp;The&nbsp; integer&nbsp; to&nbsp; output.<br>fd:&nbsp; The&nbsp; file&nbsp; descriptor&nbsp; on&nbsp; which&nbsp; to&nbsp; write.</td>
  </tr>
  <tr>
    <td>Return&nbsp; value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>write</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Outputs&nbsp; the &nbsp;integer &nbsp;’n’ &nbsp;to &nbsp;the &nbsp;given &nbsp;file &nbsp;descriptor.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br><br>

<h1>⭐️ Bonus &nbsp;part</h1>
<p>
If &nbsp;you &nbsp;completed&nbsp; the&nbsp; mandatory &nbsp;part, &nbsp;do &nbsp;not &nbsp;hesitate &nbsp;to &nbsp;go &nbsp;further &nbsp;by &nbsp;doing &nbsp;this &nbsp;extra&nbsp;
one. &nbsp;It&nbsp; will &nbsp;bring&nbsp; bonus&nbsp; points&nbsp; if&nbsp; passed &nbsp;successfully.<br>
Functions &nbsp;to&nbsp; manipulate&nbsp; memory&nbsp;and &nbsp;strings &nbsp;is&nbsp; very &nbsp;useful. &nbsp;But &nbsp;you &nbsp;will&nbsp; soon&nbsp; discover&nbsp;
that &nbsp;manipulating &nbsp;lists &nbsp;is&nbsp; even &nbsp;more &nbsp;useful.<br>
You have to use the following structure to represent a node of your list. Add its
declaration to your libft.h file:<br><br>
  typedef &nbsp;struct &nbsp;s_list<br>
  {<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;void &nbsp;*content;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;struct&nbsp; s_list&nbsp; *next;<br>
  }&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;t_list;<br><br>
<b>The &nbsp;members &nbsp;of &nbsp;the &nbsp;t_list &nbsp;struct &nbsp;are:</b><br>
<ul>
<li>content: &nbsp;The &nbsp;data &nbsp;contained &nbsp;in &nbsp;the &nbsp;node.<br>
void&nbsp; * &nbsp;allows&nbsp; to&nbsp; store &nbsp;any &nbsp;kind &nbsp;of &nbsp;data.<br>
<li>next: &nbsp;The &nbsp;address &nbsp;of &nbsp;the &nbsp;next &nbsp;node, &nbsp;or &nbsp;NULL &nbsp;if &nbsp;the&nbsp; next&nbsp; node&nbsp; is&nbsp; the&nbsp; last&nbsp; one.
</ul>
<br><br>
In &nbsp;your&nbsp; Makefile, &nbsp;add &nbsp;a &nbsp;make &nbsp;bonus &nbsp;rule &nbsp;to &nbsp;add&nbsp; the&nbsp; bonus&nbsp; functions&nbsp; to&nbsp; your&nbsp; libft.a<br><br>
<b>Implement&nbsp; the &nbsp;following &nbsp;functions &nbsp;in &nbsp;order &nbsp;to &nbsp;easily &nbsp;use your &nbsp;lists.</b>
</p>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstnew</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>t_list &nbsp;*ft_lstnew(void &nbsp;*content);</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>content: &nbsp;The &nbsp;content &nbsp;to &nbsp;create &nbsp;the &nbsp;node &nbsp;with.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>The &nbsp;new &nbsp;node</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Allocates &nbsp;(with &nbsp;malloc(3)) &nbsp;and &nbsp;returns &nbsp;a &nbsp;new node. &nbsp;The &nbsp;member&nbsp; variable &nbsp;’content’ &nbsp;is &nbsp;<br>initialized&nbsp; with &nbsp;the &nbsp;value &nbsp;of &nbsp;the &nbsp;parameter &nbsp;’content’. &nbsp;The&nbsp; variable&nbsp;
’next’&nbsp; is &nbsp;initialized &nbsp;<br>to &nbsp;NULL.</td>
  </tr>
</table>

<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstadd_front</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_lstadd_front(t_list &nbsp;**lst, &nbsp;t_list &nbsp;*new);</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The &nbsp;address &nbsp;of&nbsp; a &nbsp;pointer &nbsp;to &nbsp;the &nbsp;first &nbsp;link &nbsp;of &nbsp;a &nbsp;list.<br>new: &nbsp;The &nbsp;address&nbsp; of &nbsp;a &nbsp;pointer &nbsp;to &nbsp;the &nbsp;node &nbsp;to &nbsp;be &nbsp;added &nbsp;to &nbsp;the &nbsp;list.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>None</td>
  </tr>&nbsp;
  <tr>
    <td>Description</td>
    <td>Adds&nbsp; the &nbsp;node &nbsp;’new’ &nbsp;at &nbsp;the &nbsp;beginning &nbsp;of &nbsp;the &nbsp;list.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstsize</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>int &nbsp;ft_lstsize(t_list &nbsp;*lst);</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The &nbsp;beginning &nbsp;of &nbsp;the &nbsp;list.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>The &nbsp;length &nbsp;of &nbsp;the &nbsp;list</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Counts &nbsp;the &nbsp;number &nbsp;of &nbsp;nodes &nbsp;in &nbsp;a &nbsp;list.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstlast</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>t_list &nbsp;*ft_lstlast(t_list &nbsp;*lst);</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst:&nbsp; The&nbsp; beginning&nbsp; of &nbsp;the &nbsp;list.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>Last &nbsp;node &nbsp;of &nbsp;the &nbsp;list</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Returns &nbsp;the &nbsp;last &nbsp;node &nbsp;of&nbsp; the &nbsp;list.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstadd_back</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_lstadd_back(t_list &nbsp;**lst, &nbsp;t_list *new);</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The &nbsp;address&nbsp; of &nbsp;a &nbsp;pointer &nbsp;to &nbsp;the &nbsp;first &nbsp;link &nbsp;of &nbsp;a &nbsp;list.<br>new: &nbsp;The &nbsp;address &nbsp;of &nbsp;a &nbsp;pointer &nbsp;to &nbsp;the &nbsp;node &nbsp;to &nbsp;be &nbsp;added &nbsp;to &nbsp;the &nbsp;list.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Adds &nbsp;the &nbsp;node &nbsp;’new’ &nbsp;at&nbsp; the&nbsp; end &nbsp;of &nbsp;the&nbsp; list.</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstdelone</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_lstdelone(t_list &nbsp;*lst, &nbsp;void(*del)(void*));</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The &nbsp;node &nbsp;to &nbsp;free.<br>del:&nbsp; The &nbsp;address&nbsp; of &nbsp;the &nbsp;<br>function &nbsp;used &nbsp;to &nbsp;delete &nbsp;the &nbsp;content.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>free</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Takes&nbsp; as&nbsp; a &nbsp;parameter &nbsp;a &nbsp;node &nbsp;and &nbsp;frees &nbsp;the &nbsp;memory &nbsp;of &nbsp;the &nbsp;node’s &nbsp;content &nbsp;using &nbsp;the&nbsp;<br>function &nbsp;’del’ &nbsp;given &nbsp;as &nbsp;a&nbsp; parameter &nbsp;and &nbsp;free&nbsp; the &nbsp;node. &nbsp;The&nbsp; memory &nbsp;of &nbsp;’next’&nbsp; must <br>not &nbsp;be &nbsp;freed.</td>
  </tr>
</table>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstclear</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_lstclear(t_list&nbsp; **lst, &nbsp;void(*del)(void*));</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The &nbsp;address &nbsp;of &nbsp;a &nbsp;pointer &nbsp;to&nbsp; a &nbsp;node.<br>del: &nbsp;The &nbsp;address&nbsp; of &nbsp;the &nbsp;function &nbsp;used &nbsp;to &nbsp;delete &nbsp;the &nbsp;content &nbsp;of &nbsp;the &nbsp;node.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>free</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Deletes &nbsp;and &nbsp;frees &nbsp;the &nbsp;given &nbsp;node &nbsp;and &nbsp;every &nbsp;successor &nbsp;of &nbsp;that &nbsp;node, &nbsp;using &nbsp;the<br>function &nbsp;’del’ &nbsp;and &nbsp;free(3). &nbsp;Finally, &nbsp;the &nbsp;pointer &nbsp;to &nbsp;the &nbsp;list &nbsp;must be &nbsp;set &nbsp;to&nbsp; NULL.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>&nbsp;
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstiter</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>void &nbsp;ft_lstiter(t_list &nbsp;*lst, &nbsp;void(*f)(void *));</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The&nbsp; address &nbsp;of &nbsp;a &nbsp;pointer&nbsp; to&nbsp; a &nbsp;node.<br>f: &nbsp;The&nbsp; address&nbsp; of &nbsp;the &nbsp;function &nbsp;used &nbsp;to &nbsp;iterate &nbsp;on &nbsp;the &nbsp;list.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>None</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Iterates &nbsp;the &nbsp;list &nbsp;’lst’&nbsp; and&nbsp; applies&nbsp; the&nbsp; function &nbsp;’f’ &nbsp;on &nbsp;the &nbsp;content&nbsp; of &nbsp;each &nbsp;node.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
  </tr>
</table>
<br>
<table>
  <tr>
    <td>Function&nbsp; name</td>
    <td>ft_lstmap</td>
  </tr>
  <tr>
    <td>Prototype</td>
    <td>t_list &nbsp;*ft_lstmap(t_list &nbsp;*lst, &nbsp;void *(*f)(void *), &nbsp;void(*del)(void *));</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Parameters</td>
    <td>lst: &nbsp;The &nbsp;address&nbsp; of&nbsp; a&nbsp; pointer&nbsp; to&nbsp; a&nbsp; node.<br>f: &nbsp;The &nbsp;address &nbsp;of &nbsp;the &nbsp;function&nbsp; used&nbsp; to &nbsp;iterate &nbsp;on &nbsp;the &nbsp;list.<br>del: &nbsp;The &nbsp;address &nbsp;of &nbsp;the &nbsp;function &nbsp;used &nbsp;to &nbsp;delete &nbsp;the &nbsp;content&nbsp; of &nbsp;a &nbsp;node&nbsp; if &nbsp;needed.</td>
  </tr>
  <tr>
    <td>Return &nbsp;value</td>
    <td>The &nbsp;new&nbsp; list.<br>NULL &nbsp;if&nbsp; the&nbsp; allocation&nbsp; fails.</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc,&nbsp; free</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Iterates &nbsp;the &nbsp;list &nbsp;’lst’ &nbsp;and &nbsp;applies&nbsp; the &nbsp;function &nbsp;’f’&nbsp; on &nbsp;the &nbsp;content &nbsp;of &nbsp;each&nbsp; node.<br>Creates &nbsp;a&nbsp; new &nbsp;list &nbsp;resulting &nbsp;of &nbsp;the &nbsp;successive &nbsp;applications &nbsp;of
&nbsp;the &nbsp;function &nbsp;’f’. &nbsp;The &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>’del’ &nbsp;function &nbsp;is &nbsp;used &nbsp;to &nbsp;delete &nbsp;the &nbsp;content &nbsp;of &nbsp;a &nbsp;node &nbsp;if &nbsp;needed.</td>
  </tr>
</table>
