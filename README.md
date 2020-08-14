# react-native-intro
A way for new  feature introduction and step-by-step users guide for your react-native app

# Install
Run ```npm install react-native-intros --save``` in your Project dir

# Usage

import Intro, {IntroManage} from 'react-native-Intro';

<Intro
    content={"hello world"}
    step={1}>
</Intro>

.....

componentDidMount() {

    // and start
    var myIntro = new IntroManage();
    myIntro.start();

}

