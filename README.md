# grid-system

This is a simple and easy to use 12 columns grid system.

If what you need is only a small grid system then this is your answer.

Usage:

    <div class="gs-container">
        <div class="gs-row align-vertical">
            <div class="gs-col2 align-center"><strong>strong text</strong></div>
            <div class="gs-col4"><p>A paragraph</p></div>
            <div class="gs-col3"><span>A span</span></div>
            <div class="gs-col3"><div class="align-center">A div inside</div></div>
        </div>
    </div>

Usage with custom col padding:

    <!-- 
        You can use classes like gs-paddingtNpx, gs-paddingrNpx, gs-paddingbNpx or gs-paddinglNpx
        with gs-container class to customize gs-col* padding.
        Obs.: N can be 2, 4, 6, 8, 10, 12, 14, 16, 18 or 20
    -->
    <div class="gs-container gs-paddingt10px">
        <div class="gs-row align-vertical">
            <div class="gs-col2 align-center"><strong>strong text</strong></div>
            <div class="gs-col4"><p>A paragraph</p></div>
            <div class="gs-col3"><span>A span</span></div>
            <div class="gs-col3"><div class="align-center">A div inside</div></div>
        </div>
    </div>

Usage with no gs-col* padding at all:

    <div class="gs-container gs-no-padding">
        <div class="gs-row align-vertical">
            <div class="gs-col2 align-center"><strong>strong text</strong></div>
            <div class="gs-col4"><p>A paragraph</p></div>
            <div class="gs-col3"><span>A span</span></div>
            <div class="gs-col3"><div class="align-center">A div inside</div></div>
        </div>
    </div>
