<html>
    <head>
<!-- BEGINS: AUTO-GENERATED Museter CODE -->
<!-- unlimited Radio Hosting Museter.com plans start at $6.95 visit http://www.museter.com -->
<script type="text/javascript" src="http://www.museter.com/mrp.js"></script>
<script type="text/javascript">
MRP.insert({
'url':'http://orion.shoutca.st:8347/stream',
'codec':'mp3',
'volume':100,
'autoplay':true,
'buffering':5,
'title':'',
'bgcolor':'#FFFFFF',
'skin':'substream',
'width':180,
'height':30
});
</script>
<!-- ENDS: BEGINS: AUTO-GENERATED Museter CODE -->
        <title>{Livingroomsound Radio}</title>
        <link rel="shortcut icon" href="{Favicon}">
        <link rel="alternate" type="application/rss+xml" href="{RSS}">
        {block:Description}
            <meta name="description" content="{MetaDescription}" />
        {/block:Description}
    </head>
    <body>
        <h1>{Online Radio Station}</h1>

        {block:Description}
            <p id="description">{Description}</p>
        {/block:Description}

        <ol id="posts">
            {block:Posts}{block:Text}
                    <li class="post text">
                        {block:Title}
                            <h3><a href="{Permalink}”>{Livingroomsound Radio}</a></h3>
                        {/block:Title}{Body}
                    </li>
                {/block:Text}{block:Photo}
                    <li class="post photo">
                        <img src="{PhotoURL-500}" alt="{PhotoAlt}"/>

                        {block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </li>
                {/block:Photo}{block:Panorama}
                    <li class="post panorama">
                        {LinkOpenTag}
                            <img src="{PhotoURL-Panorama}" alt="{PhotoAlt}"/>
                        {LinkCloseTag}{block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </li>
                {/block:Panorama}{block:Photoset}
                    <li class="post photoset">
                        {Photoset-500}{block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </li>
                {/block:Photoset}{block:Quote}
                    <li class="post quote">
                        "{Quote}"

                        {block:Source}
                            <div class="source">{Source}</div>
                        {/block:Source}
                    </li>
                {/block:Quote}{block:Link}
                    <li class="post link">
                        <a href="{URL}" class="link" {Target}>{Name}</a>

                        {block:Description}
                            <div class="description">{Description}</div>
                        {/block:Description}
                    </li>
                {/block:Link}{block:Chat}
                    <li class="post chat">
                        {block:Title}
                            <h3><a href="{Permalink}">{Title}</a></h3>
                        {/block:Title}

                        <ul class="chat">
                            {block:Lines}
                                <li class="{Alt} user_{UserNumber}">
                                    {block:Label}
                                        <span class="label">{Label}</span>
                                    {/block:Label}{Line}
                                </li>
                            {/block:Lines}
                        </ul>
                    </li>
                {/block:Chat}{block:Video}
                    <li class="post video">
                        {Video-500}{block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </li>
                {/block:Video}{block:Audio}
                    <li class="post audio">
                        {AudioEmbed}{block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </li>
                {/block:Audio}{/block:Posts}
        </ol>

        <p id="footer">
            {block:PreviousPage}
                <a href="{PreviousPage}">&#171; Previous</a>
            {/block:PreviousPage}{block:NextPage}
                <a href="{NextPage}">Next &#187;</a>
            {/block:NextPage}

            <a href="/archive">Archive</a>
        </p>
    </body>
</html>
