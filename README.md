# hitting-confidence-guide
Baseball hitting confidence development program
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Step 1.2: Develop Confidence That Doesn't Fluctuate</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@400;500;600;700;800&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
            color: #1A1A1A;
            background: #FFFFFF;
        }
        
        .page {
            width: 8.5in;
            min-height: 11in;
            margin: 0 auto;
            background: white;
            padding: 0.75in;
            position: relative;
        }
        
        /* Headers and Typography */
        .step-header {
            text-align: center;
            margin-bottom: 40px;
            position: relative;
        }
        
        .step-number {
            background: #D32F2F;
            color: white;
            font-family: 'Bebas Neue', sans-serif;
            font-size: 24px;
            padding: 5px 15px;
            display: inline-block;
            margin-bottom: 10px;
        }
        
        .main-title {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 48px;
            color: #1A1A1A;
            line-height: 1;
            margin-bottom: 15px;
        }
        
        .subtitle {
            font-size: 18px;
            color: #757575;
            font-weight: 500;
        }
        
        .section-title {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 32px;
            color: #D32F2F;
            margin: 40px 0 20px;
            text-align: center;
        }
        
        /* Content Blocks */
        .opening-quote {
            background: #D32F2F;
            color: white;
            padding: 30px;
            margin: 30px 0;
            position: relative;
            font-size: 24px;
            font-weight: 600;
            text-align: center;
        }
        
        .opening-quote::before,
        .opening-quote::after {
            content: '"';
            font-size: 60px;
            position: absolute;
            opacity: 0.3;
        }
        
        .opening-quote::before {
            top: -10px;
            left: 20px;
        }
        
        .opening-quote::after {
            bottom: -40px;
            right: 20px;
        }
        
        .truth-box {
            background: #f8f8f8;
            border-left: 5px solid #D32F2F;
            padding: 20px;
            margin: 20px 0;
        }
        
        .warning-signs {
            background: #1A1A1A;
            color: white;
            padding: 30px;
            margin: 40px 0;
        }
        
        .warning-signs h3 {
            color: #D32F2F;
            font-family: 'Bebas Neue', sans-serif;
            font-size: 28px;
            margin-bottom: 20px;
        }
        
        .warning-list {
            list-style: none;
        }
        
        .warning-list li {
            padding: 10px 0;
            border-bottom: 1px solid #333;
            display: flex;
            align-items: center;
        }
        
        .warning-list li:last-child {
            border-bottom: none;
        }
        
        .warning-list li::before {
            content: '⚠️';
            margin-right: 15px;
            font-size: 20px;
        }
        
        /* Performance States */
        .performance-states {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin: 40px 0;
        }
        
        .state-card {
            border: 2px solid;
            padding: 20px;
            border-radius: 10px;
        }
        
        .state-card.peak {
            border-color: #4CAF50;
            background: #f1f8e9;
        }
        
        .state-card.struggling {
            border-color: #D32F2F;
            background: #ffebee;
        }
        
        .state-header {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 24px;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .state-list {
            list-style: none;
        }
        
        .state-list li {
            display: flex;
            align-items: center;
            padding: 8px 0;
            border-bottom: 1px solid rgba(0,0,0,0.1);
        }
        
        .state-list li:last-child {
            border-bottom: none;
        }
        
        /* Elite Checklist */
        .checklist-item {
            background: white;
            border: 2px solid #D32F2F;
            margin: 30px 0;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .checklist-header {
            background: #D32F2F;
            color: white;
            padding: 15px 20px;
            font-family: 'Bebas Neue', sans-serif;
            font-size: 28px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .checklist-content {
            padding: 25px;
        }
        
        .standard-box {
            background: #f8f8f8;
            padding: 20px;
            margin-bottom: 20px;
            border-left: 4px solid #1A1A1A;
        }
        
        .builders-box {
            background: #fff3f3;
            padding: 20px;
            border-left: 4px solid #D32F2F;
        }
        
        /* Pro Spotlights */
        .pro-spotlight {
            background: #1A1A1A;
            color: white;
            padding: 30px;
            margin: 40px 0;
            border-radius: 10px;
            position: relative;
            overflow: hidden;
        }
        
        .pro-spotlight::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 200px;
            height: 200px;
            background: #D32F2F;
            opacity: 0.1;
            border-radius: 50%;
            transform: translate(50%, -50%);
        }
        
        .pro-header {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 24px;
            color: #D32F2F;
            margin-bottom: 15px;
        }
        
        .pro-quote {
            font-style: italic;
            font-size: 18px;
            margin: 20px 0;
            position: relative;
            padding-left: 30px;
        }
        
        .pro-quote::before {
            content: '"';
            position: absolute;
            left: 0;
            top: -10px;
            font-size: 50px;
            color: #D32F2F;
            opacity: 0.5;
        }
        
        /* Framework Diagrams */
        .framework {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 40px 0;
            padding: 30px;
            background: #f8f8f8;
        }
        
        .framework-step {
            flex: 1;
            text-align: center;
            padding: 20px;
            background: white;
            border: 2px solid #D32F2F;
            margin: 0 10px;
            border-radius: 10px;
            position: relative;
        }
        
        .framework-step .step-icon {
            font-size: 32px;
            margin-bottom: 10px;
        }
        
        .framework-step h4 {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 24px;
            color: #D32F2F;
            margin-bottom: 10px;
        }
        
        .framework-arrow {
            font-size: 24px;
            color: #D32F2F;
        }
        
        /* Confidence System */
        .confidence-pillars {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            margin: 40px 0;
        }
        
        .pillar {
            background: #1A1A1A;
            color: white;
            padding: 25px;
            border-radius: 10px;
            position: relative;
        }
        
        .pillar-number {
            position: absolute;
            top: -15px;
            left: 20px;
            background: #D32F2F;
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Bebas Neue', sans-serif;
            font-size: 24px;
        }
        
        .pillar h4 {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 22px;
            margin-bottom: 15px;
            margin-top: 10px;
        }
        
        /* Daily Plan */
        .daily-plan {
            background: #f8f8f8;
            padding: 30px;
            margin: 40px 0;
            border-radius: 10px;
        }
        
        .plan-timeline {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
        
        .timeline-step {
            flex: 1;
            text-align: center;
            padding: 20px;
            background: white;
            margin: 0 10px;
            border-radius: 10px;
            border: 2px solid #D32F2F;
        }
        
        .timeline-step h5 {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 20px;
            color: #D32F2F;
            margin-bottom: 10px;
        }
        
        /* Final Commitment */
        .commitment-section {
            background: #D32F2F;
            color: white;
            padding: 50px;
            margin: 40px -30px -30px;
            text-align: center;
        }
        
        .commitment-title {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 48px;
            margin-bottom: 30px;
        }
        
        .commitment-questions {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin: 40px 0;
        }
        
        .commitment-card {
            background: white;
            color: #1A1A1A;
            padding: 25px;
            border-radius: 10px;
            text-align: left;
        }
        
        .commitment-card h5 {
            font-family: 'Bebas Neue', sans-serif;
            font-size: 20px;
            color: #D32F2F;
            margin-bottom: 15px;
        }
        
        .final-message {
            font-size: 24px;
            font-weight: 700;
            margin-top: 40px;
            line-height: 1.4;
        }
        
        /* Print Styles */
        @media print {
            .page {
                box-shadow: none;
                margin: 0;
            }
            
            .commitment-section {
                margin: 40px 0 0;
            }
        }
    </style>
</head>
<body>
    <div class="page">
        <!-- Header Section -->
        <div class="step-header">
            <div class="step-number">⚾ STEP 1.2</div>
            <h1 class="main-title">DEVELOP CONFIDENCE<br>THAT DOESN'T FLUCTUATE</h1>
            <div class="subtitle">From Inconsistent Performance → To Unshakeable Confidence</div>
        </div>

        <!-- Opening Quote -->
        <div class="opening-quote">
            If I get a hit... then I'll feel confident.<br>
            If I'm going good... then I'll trust my swing.
        </div>

        <!-- Truth Section -->
        <div class="truth-box">
            <h3>THE BIGGEST TRAP IN HITTING</h3>
            <p>Tying your confidence to your results.</p>
            <ul style="margin-top: 15px;">
                <li>✅ Even the best hitters fail 7 out of 10 times</li>
                <li>✅ If your confidence rises and falls with every at-bat... you're giving your power away</li>
            </ul>
        </div>

        <!-- Warning Signs -->
        <div class="warning-signs">
            <h3>WHERE YOU ARE NOW: THE CONFIDENCE TRAP</h3>
            <ul class="warning-list">
                <li>Your confidence vanishes after a few hitless at-bats</li>
                <li>You're overthinking mechanics during games instead of competing</li>
                <li>The game suddenly feels faster when you're struggling</li>
                <li>You hesitate on pitches you should attack</li>
                <li>Your body tightens in pressure situations</li>
                <li>You have no clear plan when facing tough pitchers</li>
            </ul>
        </div>

        <!-- Performance States -->
        <div class="section-title">UNDERSTANDING YOUR PERFORMANCE STATES</div>
        <div class="performance-states">
            <div class="state-card peak">
                <div class="state-header">
                    🔥 PEAK PERFORMANCE STATE
                </div>
                <ul class="state-list">
                    <li>💪 HIGH CONFIDENCE</li>
                    <li>⏱️ Game feels SLOW</li>
                    <li>🧘 Mind is QUIET</li>
                    <li>🔍 Focus on BALL</li>
                    <li>🏹 DECISIVE approach</li>
                    <li>🌊 Body feels LOOSE</li>
                </ul>
            </div>
            <div class="state-card struggling">
                <div class="state-header">
                    🌧️ STRUGGLING STATE
                </div>
                <ul class="state-list">
                    <li>😟 LOW CONFIDENCE</li>
                    <li>🏃 Game feels FAST</li>
                    <li>🗣️ Mind is NOISY</li>
                    <li>🔧 Focus on MECHANICS</li>
                    <li>🤔 HESITANT approach</li>
                    <li>🪨 Body feels TIGHT</li>
                </ul>
            </div>
        </div>

        <!-- Elite Hitter's Checklist -->
        <div class="section-title">THE ELITE HITTER'S CHECKLIST</div>
        
        <div class="checklist-item">
            <div class="checklist-header">
                1️⃣ AM I CONFIDENT?
            </div>
            <div class="checklist-content">
                <div class="standard-box">
                    <h4>THE ELITE STANDARD:</h4>
                    <ul>
                        <li>Walking to the plate with command presence</li>
                        <li>Positive, aggressive body language</li>
                        <li>Internal self-talk that reinforces your identity</li>
                    </ul>
                </div>
                <div class="builders-box">
                    <h4>CONFIDENCE BUILDERS:</h4>
                    <ul>
                        <li>Physical confidence triggers (chest up, controlled breathing)</li>
                        <li>Pre-at-bat visualization of success</li>
                        <li>Identity-based confidence statements</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- Pro Spotlight -->
        <div class="pro-spotlight">
            <div class="pro-header">🗣️ PRO INSIGHT: VLADIMIR GUERRERO JR.</div>
            <p>Vladimir Guerrero Jr. has become one of MLB's most dangerous hitters not just because of his raw power, but because of how he prepares. His confidence at the plate is built long before game time.</p>
            <div class="pro-quote">
                He treats every cage session as a chance to "install" his approach and timing—so when he steps into the box, there's no searching for confidence. It's already there because his preparation made it automatic.
            </div>
        </div>

        <!-- 3R Framework -->
        <div class="section-title">THE 3R ADJUSTMENT FRAMEWORK</div>
        <div class="framework">
            <div class="framework-step">
                <div class="step-icon">🔍</div>
                <h4>RECOGNIZE</h4>
                <p>Identify what happened</p>
                <p>Spot the pattern</p>
                <p>Find the opportunity</p>
            </div>
            <div class="framework-arrow">→</div>
            <div class="framework-step">
                <div class="step-icon">🔄</div>
                <h4>RESET</h4>
                <p>Clear your mind</p>
                <p>Physical reset cue</p>
                <p>Return to present</p>
            </div>
            <div class="framework-arrow">→</div>
            <div class="framework-step">
                <div class="step-icon">🚀</div>
                <h4>RESPOND</h4>
                <p>Make adjustment</p>
                <p>Trust completely</p>
                <p>Execute with confidence</p>
            </div>
        </div>

        <!-- Confidence System -->
        <div class="section-title">BUILDING YOUR COMPLETE CONFIDENCE SYSTEM</div>
        <div class="confidence-pillars">
            <div class="pillar">
                <div class="pillar-number">1</div>
                <h4>PREPARATION CONFIDENCE</h4>
                <p>Consistent pre-game routine</p>
                <p>Deliberate practice</p>
                <p>Game planning</p>
            </div>
            <div class="pillar">
                <div class="pillar-number">2</div>
                <h4>PROCESS CONFIDENCE</h4>
                <p>Elite Hitter's Checklist</p>
                <p>Focus on approach quality</p>
                <p>Hunting mindset</p>
            </div>
            <div class="pillar">
                <div class="pillar-number">3</div>
                <h4>ADJUSTMENT CONFIDENCE</h4>
                <p>3R Framework</p>
                <p>Quick changes</p>
                <p>Learning from at-bats</p>
            </div>
            <div class="pillar">
                <div class="pillar-number">4</div>
                <h4>IDENTITY CONFIDENCE</h4>
                <p>Unshakeable belief</p>
                <p>Clear definition</p>
                <p>Performance standards</p>
            </div>
        </div>

        <!-- Daily Plan -->
        <div class="daily-plan">
            <h3 style="text-align: center; font-family: 'Bebas Neue', sans-serif; font-size: 28px; margin-bottom: 20px;">YOUR CONFIDENCE BUILDER PLAN</h3>
            <div class="plan-timeline">
                <div class="timeline-step">
                    <h5>MORNING</h5>
                    <p>Identity Review</p>
                    <p>Confidence Activation</p>
                </div>
                <div class="timeline-step">
                    <h5>PRE-PERFORMANCE</h5>
                    <p>Visualization</p>
                    <p>Physical Prep</p>
                </div>
                <div class="timeline-step">
                    <h5>POST-PERFORMANCE</h5>
                    <p>Process Evaluation</p>
                    <p>Adjustment Planning</p>
                </div>
            </div>
        </div>

        <!-- Final Commitment -->
        <div class="commitment-section">
            <h2 class="commitment-title">🏆 THE GAME-READY COMMITMENT</h2>
            <p style="font-size: 20px; margin-bottom: 30px;">Success isn't about waiting for confidence to show up — it's about building it through intentional work.</p>
            
            <div class="commitment-questions">
                <div class="commitment-card">
                    <h5>✅ COMMITMENT #1</h5>
                    <p>What is ONE element of your confidence system that you will commit to this week?</p>
                </div>
                <div class="commitment-card">
                    <h5>✅ COMMITMENT #2</h5>
                    <p>How will you practice it with purpose — not just reps, but real focus?</p>
                </div>
                <div class="commitment-card">
                    <h5>✅ COMMITMENT #3</h5>
                    <p>What will your "check-in" look like after each game or practice?</p>
                </div>
            </div>
            
            <div class="final-message">
                Confidence is a choice you make before the at-bat even begins.<br>
                The next pitch is your chance. Own it.
            </div>
        </div>
    </div>
</body>
</html>
