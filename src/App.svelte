<script>
import P from './P.svelte';
import H5 from './H5.svelte';
</script>

<style>
@import 'tailwindcss/preflight';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';

.to-form {
	margin-top: -80px;
	background: linear-gradient(to right, red, purple);
}

.outlined {
	max-width: 868px;
}

.video-placeholder {
	border: 10px solid black;
	width: 600px;
	height: 400px;
	max-width: 100%;
	margin-bottom: -200px;
}

.last {
	width: 480px;
}

</style>

<div class="pa-0 ma-0 text-xl">
	<div class="w-full flex flex-wrap justify-between mt-0 py-2 bg-grey text-center">
		<div class="container py-20">
			<div class="text-xs">«апполония» + <span class="text-red">театр на таганке</span></div>
			<div class="font-bold py-5 text-5xl">С М Е Щ Е Н И Е</div>
			<div class="text-xs mb-10">театральная лаборатория, какой она должна быть</div>
			<div class="video-placeholder mx-auto"></div>
		</div>
	</div>
	<div class="container mx-auto pb-10 pt-32">
		<div class="flex pt-32">
			<div class="flex-1 pa-10 px-3">
				<img alt="beton" src="/img/1.jpg" width="250">
			</div>
			<div class="flex-1 px-3 align-middle">
				Нам всем нужен новый театр. Каким он должен быть и будет — неизвестно. Хорошо, что теперь есть время и место об этом подумать. Проект «аполлония» и Театр на Таганке запускают арт-лабораторию «смещение». Нас интересуют экстремальные в своей радикальности форматы нового театра, — такого театра, который перестал быть театром.
			</div>
		</div>
		<P>Совершенно точно понятно сейчас одно: делать театральные лаборатории так, как их делают сегодня в России, уже давно незачем. Остаётся вопрос: «а как их тогда делать?» Мы не знаем. Но попробуем это выяснить в последнюю неделю мая. </P>
		<P>В рамках этой лаборатории можно всё. Но есть одно условие: </P>
	</div>
	<div class="mx-auto outlined text-center">
		<P><H5>никаких живых людей в сценическом пространстве в рамках проектов.</H5></P>
	</div>
	<div class="container mx-auto py-10">
		<P>Ни актёров, ни перформеров, вообще никаких людей. Вы можете придумывать новый театр с помощью чего угодно — за вычетом живых существ. Да, животные тоже считаются. Нет, растения можно, но зачем?</P>
		<P>В работе можно использовать аудио и видеозаписи с наличием людей, но они должны быть предзаписанными, а не даваться в онлайн-режиме. Если вы используете механизмы, нуждающиеся в управлении человеком из-за сцены, — это допускается. </P>
	</div>
	<div class="outlined flex mx-auto py-10">
		<div class="flex-1 px-10">
			<img alt="beton" src="/img/2.jpg">
		</div>
		<div class="flex-1 px-10">
			<img alt="beton" src="/img/3.jpg">
		</div>
	</div>
	<div class="container pb-10">
		<P>лаборатория пройдёт с 27 мая по 2 июня на малой сцене театра на таганке; вы можете использовать эту площадку, а можете не использовать и предожить проект на улице или в онлайне; использование дополнительных зон театра обговаривается.</P>
	</div>
	<div class="mx-auto outlined text-center">
		<P><H5>почему театральные лаборатории в россии в основном такие чудовищные?</H5></P>
	</div>
	<div class="container pb-10">
		<P>потому что они предъявляют такие требования к участникам, которые моментально тушат любую креативную энергию. в «смещении» всё не так:</P>
	</div>
	<div class="outlined mx-auto flex py-10">
		<div class="flex-1 px-10">
			<img alt="beton" src="/img/4.jpg">
		</div>
		<div class="flex-1 px-10">
			<img alt="beton" src="/img/5.jpg">
		</div>
	</div>
	<div class="container">
		<P><b>здесь нет ограничений по времени.</b> показ может длиться минуту, 24 часа или всю неделю, если это оставляет возможность показа других проектов</P>
		<P><b>не нужно профессиональное образование.</b> здесь никто не попросит вас показать диплом, интересны только ваши идеи</P>
		<P><b>у нас нет ограничений по возрасту, бэкграунду и вашей профессиональной принадлежности.</b> это арт-инкубатор для художников, инженеров, режиссёров, архитекторов, актёров, хореографов и композиторов, для креаторов внежанрового искусства, носителей нового воображения на стыке символического и цифрового</P>
		<P><b>здесь нет тематических ограничений, материалом для показа может стать что угодно.</b> никто не будет заставлять вас работать с драматургией или чем-то ещё</P>
		<P><b>в этой лаборатории нет жюри и экспертного совета, не может быть и «победителей».</b> оценивать и ранжировать проекты в рамках лаборатории с такой степенью горизонтальности и свободы было бы просто абсурдом.
			<i>несмотря на это, по итогам лаборатории, разумеется, рассчитывает на новый спектакль в репертуар.</i></P>
		<P class="last">Вы свободны указывать в заявке тот технический райдер, который вам необходим, однако важно помнить о естественных ресурсных ограничениях театра, в котором проходит эта лаборатория. Возможность реализации того или иного события мы будем обсуждать отдельно с каждым участником. По умолчанию театр не обеспечивает проезд и проживание участникам из других городов, но мы оставляем за собой возможность предложить перелёт до Москвы участникам с особо визионерскими заявками. Воронка приёма заявок будет постепенно закрываться в период с 5 мая по 10-е. </P>
	</div>
	<div class="flex to-form py-20">
		<div class="container text-center">
	 	<a href="/form" class="font-bold text-white text-4xl"><i>Заполнить форму</i></a>
	 </div>
	</div>
	<div class="container py-10 text-2xl text-center">
		<a class="text-purple" href="vk.com">вк</a>
		<a class="text-purple" href="ttt">тлг</a>
		<a class="text-purple" href="ttt">фб</a> 
		<a class="text-purple" href="ttt">инст</a>
	</div>

</div>