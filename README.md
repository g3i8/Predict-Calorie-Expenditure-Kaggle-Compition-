The goal is to predict how many calories were burned during a workout.

The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mrow class="MJX-TeXAtom-ORD">
    <mtext>RMSLE</mtext>
  </mrow>
  <mo>=</mo>
  <msup>
    <mrow>
      <mo>(</mo>
      <mfrac>
        <mn>1</mn>
        <mi>n</mi>
      </mfrac>
      <munderover>
        <mo>&#x2211;<!-- ∑ --></mo>
        <mrow class="MJX-TeXAtom-ORD">
          <mi>i</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mi>n</mi>
      </munderover>
      <mrow>
        <mo>(</mo>
        <mi>log</mi>
        <mo>&#x2061;<!-- ⁡ --></mo>
        <mo stretchy="false">(</mo>
        <mn>1</mn>
        <mo>+</mo>
        <msub>
          <mrow class="MJX-TeXAtom-ORD">
            <mover>
              <mi>y</mi>
              <mo>&#x005E;<!-- ^ --></mo>
            </mover>
          </mrow>
          <mi>i</mi>
        </msub>
        <mo stretchy="false">)</mo>
        <mo>&#x2212;<!-- − --></mo>
        <mi>log</mi>
        <mo>&#x2061;<!-- ⁡ --></mo>
        <mo stretchy="false">(</mo>
        <mn>1</mn>
        <mo>+</mo>
        <msub>
          <mi>y</mi>
          <mi>i</mi>
        </msub>
        <mo stretchy="false">)</mo>
        <mo>)</mo>
      </mrow>
      <mo>)</mo>
    </mrow>
    <mrow class="MJX-TeXAtom-ORD">
      <mfrac>
        <mn>1</mn>
        <mn>2</mn>
      </mfrac>
    </mrow>
  </msup>
</math>
