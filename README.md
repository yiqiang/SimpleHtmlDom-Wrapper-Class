sample usage:

$dom=new Dom;

$nodes=$dom->str_get_html($content);

$text=$nodes->find('p[id=article]',0)->innertext;