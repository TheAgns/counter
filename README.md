[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=TheAgns&theme=dark&hide_border=true)](https://git.io/streak-stats)
![Profile Shown](https://komarev.com/ghpvc/?username=TheAgns)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=TheAgns&theme=dark&show_icons=true)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=TheAgns&theme=light&show_icons=true)
##Her
<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
