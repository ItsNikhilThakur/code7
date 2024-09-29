# code7
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Form</title>
    <style>
      /* Red star after required fields */
      .red-star {
        color: red;
        margin-left: 2px;
      }

      /* Style for checkbox */
      .checkbox input[type="checkbox"] {
        width: 16px;
        height: 16px;
        cursor: pointer;
      }

      /* Curve CSS */
      .curve {
        background-color: #fff;
        height: 100px; /* Height of the curve */
        position: relative;
      }

      .curve::before {
        content: '';
        display: block;
        position: absolute;
        left: 0;
        right: 0;
        bottom: 0;
        height: 100px; /* Adjust height of the curve */
        background-color: #ff0000; /* Color of the curve */
        border-radius: 0 0 50% 50%; /* Create the curve effect */
        z-index: -1;
      }
    </style>
  </head>
  <body>
    <div class="frame">
      <div class="overlap-wrapper">
        <div class="overlap">
          <img class="image" src="img/image-2.png" />
          <div class="logo-dfscircle-wrapper">
            <img class="logo-dfscircle" src="images/dfscircle-vertical.svg" />
          </div>
          <div class="div">
            <img class="banner" src="img/banner-4-3.svg" />
            <div class="div-2">
              <div class="div-3">
                <div class="title-banner">
                  <div class="text-wrapper">DFS Exclusive</div>
                </div>
                <div class="div-4">
                  <div class="div-5">
                    <div class="image-wrapper">
                      <img class="img" src="img/image-11.png" />
                    </div>
                    <div class="div-6">
                      <p class="p">
                        Armani Beauty Exclusive VIP Workshop (T Galleria by DFS, Macau, Shoppes at Four Seasons)
                      </p>
                    </div>
                  </div>
                  <p class="text-wrapper-2">
                    Armani Beauty sincerely invites you to experience personalized Crema Nera and Armani Privé
                    consultation (about 30 minutes). Upon completion, you can enjoy the Crema Nera Trial Kit (worth MOP
                    1,525)
                  </p>
                </div>
              </div>
              <div class="div-7">
                <div class="session-title">
                  <div class="icon-COPYME">
                    <img class="element-loyalty-opening" src="img/opening-hours.svg" />
                  </div>
                  <div class="text-wrapper-3">Workshop time :</div>
                </div>
                <p class="february">February 7-8, 10-18, 23-25 2pm to 8pm</p>
              </div>
              <div class="div-8">
                <div class="div-9">
                  <p class="text-wrapper-4">Please fill in the following contact details</p>
                  <div class="standard-input-and">
                    <div class="text-input">
                      <div class="paragraph-container">
                        <div class="title">First Name</div>
                        <div class="red-star">*</div>
                      </div>
                      <div class="icon"></div>
                    </div>
                  </div>
                  <div class="standard-input-and">
                    <div class="text-input">
                      <div class="paragraph-container">
                        <div class="title">Last Name</div>
                        <div class="red-star">*</div>
                      </div>
                      <div class="icon"></div>
                    </div>
                  </div>
                  <div class="standard-input-and">
                    <div class="text-input">
                      <div class="paragraph-container">
                        <div class="title">Email</div>
                        <div class="red-star">*</div>
                      </div>
                      <div class="icon"></div>
                    </div>
                  </div>
                  <div class="standard-input-and">
                    <div class="div-10">
                      <div class="text-input-2">
                        <div class="container">
                          <div class="paragraph-container-2">
                            <div class="text-wrapper-6">Country code</div>
                            <div class="red-star">*</div>
                          </div>
                          <div class="text-wrapper-8">+852</div>
                        </div>
                        <div class="icon-COPYME-wrapper">
                          <div class="div-11">
                            <img class="element-generic-arrow" src="img/arrow-down.svg" />
                          </div>
                        </div>
                      </div>
                      <div class="button">
                        <div class="horizontal-container">
                          <div class="paragraph-container-2">
                            <div class="text-wrapper-9">Mobile number</div>
                            <div class="red-star">*</div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="checkbox-with-text">
                    <div class="checkbox">
                      <input type="checkbox" />
                    </div>
                    <div class="div-12">
                      <p class="remember-the">
                        By submitting the form, I understand and agree that DFS is a global company and that my DFS
                        CIRCLE data and order information will be processed overseas, subject to applicable laws and
                        regulations. Also, in order to provide better service, DFS stores around the world will have the
                        possibility to access my DFS CIRCLE account information and event registeration for the purpose
                        of event follow-up.
                      </p>
                      <div class="red-star">*</div>
                    </div>
                  </div>
                  <div class="div-10">
                    <div class="checkbox">
                      <input type="checkbox" />
                    </div>
                    <div class="div-12">
                      <p class="remember-the">
                        <span class="span"
                          >By submitting the form, I acknowledge and agree to receive phone call/SMS/text and/or email
                          messages via the contact information provided concerning the event registeration updates or
                          notifications, and as otherwise permitted by our privacy policy. To better understand how DFS
                          protects your data, please refer to our Data Privacy Policy </span
                        >
                        <a href="https://www.dfs.com/en/hong-kong/privacy-policy-hk" target="_blank" rel="noopener noreferrer"
                          ><span class="text-wrapper-11">here</span></a
                        >
                        <span class="span"
                          >. Should you have any questions, please feel free to contact our Data Protection Officer at
                          dpo@dfs.com.</span
                        >
                      </p>
                      <div class="red-star">*</div>
                    </div>
                  </div>
                </div>
                <button class="standard-button-wrapper">
                  <button class="standard-button">
                    <div class="text">Confirm</div>
                  </button>
                </button>
                <div class="div-13">
                  <p class="text-wrapper-12">
                    After submission, a DFS representative will contact you for appointment details
                  </p>
                  <p class="text-wrapper-13">Limited availability, first-come, first served basis.</p>
                </div>
              </div>
            </div>
            <div class="bottom">
              <div class="text-2">
                <div class="row">
                  <div class="text-wrapper-14">Terms &amp; Conditions</div>
                  <div class="div-11">
                    <div class="ellipse"></div>
                  </div>
                  <div class="text-wrapper-14">Privacy Policy</div>
                </div>
                <p class="text-wrapper-15">
                  © 2024 DFS Group Ltd. Enjoy duty free shopping with DFS at our airport duty free shops and downtown T
                  Galleria stores worldwide
                </p>
              </div>
              <!-- Curve element added here -->
              <div class="curve"></div>
              <div class="group">
                <div class="overlap-group">
                  <img class="logo-DFS" src="img/DFS.svg" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
///////////////////////
.frame {
    background-color: #ffffff;
    display: flex;
    flex-direction: row;
    justify-content: center;
    width: 100%;
  }
  
  .frame .overlap-wrapper {
    background-color: #ffffff;
    width: 375px;
    height: 1945px;
  }
  
  .frame .overlap {
    position: relative;
    height: 1809px;
  }
  
  .frame .image {
    position: absolute;
    width: 375px;
    height: 790px;
    top: 62px;
    left: 0;
    object-fit: cover;
  }
  
  .frame .logo-dfscircle-wrapper {
    display: flex;
    flex-direction: column;
    width: 375px;
    height: 102px;
    align-items: center;
    gap: 10px;
    padding: 24px 0px;
    position: absolute;
    top: 0;
    left: 0;
    background-color: #ffffff;
  }
  
  .frame .logo-dfscircle {
    position: relative;
    height: 54px;
  }
  
  .frame .div {
    display: inline-flex;
    flex-direction: column;
    align-items: flex-start;
    position: absolute;
    top: 126px;
    left: 16px;
    background-color: #ffffff;
    border-radius: 16px;
    overflow: hidden;
    box-shadow: var(--white-bg-shadow);
  }
  
  .frame .banner {
    position: relative;
    width: 343px;
    height: 256px;
  }
  
  .frame .div-2 {
    display: flex;
    flex-direction: column;
    width: 343px;
    align-items: center;
    gap: 16px;
    padding: 0px 16px 24px;
    position: relative;
    flex: 0 0 auto;
    background-color: #ffffff;
  }
  
  .frame .div-3 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 16px 0px 0px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .title-banner {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 2px;
    padding: 4px 0px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .text-wrapper {
    position: relative;
    align-self: stretch;
    margin-top: -1.25px;
    font-family: var(--body-14-semibold-font-family);
    font-weight: var(--body-14-semibold-font-weight);
    color: var(--branded-color-purpledefault-781556);
    font-size: var(--body-14-semibold-font-size);
    text-align: center;
    letter-spacing: var(--body-14-semibold-letter-spacing);
    line-height: var(--body-14-semibold-line-height);
    font-style: var(--body-14-semibold-font-style);
  }
  
  .frame .div-4 {
    display: flex;
    flex-direction: column;
    width: 311px;
    align-items: center;
    gap: 8px;
    position: relative;
    flex: 0 0 auto;
  }
  
  .frame .div-5 {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .image-wrapper {
    display: inline-flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    padding: 8px 0px;
    position: relative;
    flex: 0 0 auto;
  }
  
  .frame .img {
    position: relative;
    width: 203px;
    height: 24px;
  }
  
  .frame .div-6 {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    padding: 16px 0px 0px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .p {
    margin-top: -1px;
    font-family: var(--title-20-semibold-font-family);
    font-weight: var(--title-20-semibold-font-weight);
    font-size: var(--title-20-semibold-font-size);
    line-height: var(--title-20-semibold-line-height);
    position: relative;
    align-self: stretch;
    color: #000000;
    text-align: center;
    letter-spacing: var(--title-20-semibold-letter-spacing);
    font-style: var(--title-20-semibold-font-style);
  }
  
  .frame .text-wrapper-2 {
    font-family: var(--body-13-regular-font-family);
    font-weight: var(--body-13-regular-font-weight);
    font-size: var(--body-13-regular-font-size);
    line-height: var(--body-13-regular-line-height);
    position: relative;
    align-self: stretch;
    color: #000000;
    text-align: center;
    letter-spacing: var(--body-13-regular-letter-spacing);
    font-style: var(--body-13-regular-font-style);
  }
  
  .frame .div-7 {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px 0px 8px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .session-title {
    display: flex;
    align-items: center;
    gap: 8px;
    padding: 8px 16px 8px 0px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
    background-color: var(--backgroundlv1-ffffff);
  }
  
  .frame .icon-COPYME {
    display: inline-flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
    position: relative;
    flex: 0 0 auto;
  }
  
  .frame .element-loyalty-opening {
    position: relative;
    width: 24px;
    height: 24px;
  }
  
  .frame .text-wrapper-3 {
    position: relative;
    width: fit-content;
    font-family: var(--body-16-semibold-font-family);
    font-weight: var(--body-16-semibold-font-weight);
    color: var(--textdefaultblack-000000);
    font-size: var(--body-16-semibold-font-size);
    letter-spacing: var(--body-16-semibold-letter-spacing);
    line-height: var(--body-16-semibold-line-height);
    white-space: nowrap;
    font-style: var(--body-16-semibold-font-style);
  }
  
  .frame .february {
    position: relative;
    align-self: stretch;
    font-family: var(--body-14-regular-font-family);
    font-weight: var(--body-14-regular-font-weight);
    color: var(--textdefaultblack-000000);
    font-size: var(--body-14-regular-font-size);
    letter-spacing: var(--body-14-regular-letter-spacing);
    line-height: var(--body-14-regular-line-height);
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 1;
    -webkit-box-orient: vertical;
    font-style: var(--body-14-regular-font-style);
  }
  
  .frame .div-8 {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .div-9 {
    gap: 16px;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .text-wrapper-4 {
    position: relative;
    align-self: stretch;
    margin-top: -1px;
    font-family: var(--body-14-regular-font-family);
    font-weight: var(--body-14-regular-font-weight);
    color: var(--colorgrey80-333333);
    font-size: var(--body-14-regular-font-size);
    letter-spacing: var(--body-14-regular-letter-spacing);
    line-height: var(--body-14-regular-line-height);
    font-style: var(--body-14-regular-font-style);
  }
  
  .frame .standard-input-and {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 4px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .text-input {
    display: flex;
    height: 56px;
    align-items: center;
    justify-content: space-between;
    padding: 16px;
    position: relative;
    align-self: stretch;
    width: 100%;
    background-color: var(--textdefaultwhite-ffffff);
    border-radius: 8px;
    border: 1px solid;
    border-color: var(--linedefault-dbdbdb);
  }
  
  .frame .paragraph-container {
    display: flex;
    width: 279px;
    align-items: center;
    position: relative;
    align-self: stretch;
  }
  
  .frame .title {
    position: relative;
    width: fit-content;
    font-family: var(--body-16-regular-font-family);
    font-weight: var(--body-16-regular-font-weight);
    color: var(--textlight-767676);
    font-size: var(--body-16-regular-font-size);
    letter-spacing: var(--body-16-regular-letter-spacing);
    line-height: var(--body-16-regular-line-height);
    white-space: nowrap;
    font-style: var(--body-16-regular-font-style);
  }
  
  .frame .text-wrapper-5 {
    position: relative;
    width: fit-content;
    font-family: var(--mob-body-XS-reg-10px-font-family);
    font-weight: var(--mob-body-XS-reg-10px-font-weight);
    color: var(--system-colorcritical-ea002a);
    font-size: var(--mob-body-XS-reg-10px-font-size);
    letter-spacing: var(--mob-body-XS-reg-10px-letter-spacing);
    line-height: var(--mob-body-XS-reg-10px-line-height);
    white-space: nowrap;
    font-style: var(--mob-body-XS-reg-10px-font-style);
  }
  
  .frame .icon {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    padding: 4px 0px;
    position: relative;
    flex: 0 0 auto;
    margin-left: -16px;
  }
  
  .frame .div-10 {
    display: flex;
    align-items: flex-start;
    gap: 8px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .text-input-2 {
    display: flex;
    height: 56px;
    align-items: center;
    justify-content: space-between;
    padding: 16px;
    position: relative;
    flex: 1;
    flex-grow: 1;
    background-color: var(--textdefaultwhite-ffffff);
    border-radius: 8px;
    border: 1px solid;
    border-color: var(--linedefault-dbdbdb);
  }
  
  .frame .container {
    display: flex;
    flex-direction: column;
    width: 103px;
    align-items: flex-start;
    gap: 4px;
    position: relative;
    margin-top: -8px;
    margin-bottom: -8px;
  }
  
  .frame .paragraph-container-2 {
    display: flex;
    width: 36px;
    align-items: flex-start;
    position: relative;
    flex: 0 0 auto;
  }
  
  .frame .text-wrapper-6 {
    position: relative;
    width: fit-content;
    margin-top: -1px;
    margin-right: -36px;
    font-family: var(--body-12-regular-font-family);
    font-weight: var(--body-12-regular-font-weight);
    color: var(--textlight-767676);
    font-size: var(--body-12-regular-font-size);
    letter-spacing: var(--body-12-regular-letter-spacing);
    line-height: var(--body-12-regular-line-height);
    white-space: nowrap;
    font-style: var(--body-12-regular-font-style);
  }
  
  .frame .text-wrapper-7 {
    position: relative;
    width: fit-content;
    margin-top: -1px;
    margin-right: -42px;
    font-family: var(--body-12-regular-font-family);
    font-weight: var(--body-12-regular-font-weight);
    color: var(--system-colorcritical-ea002a);
    font-size: var(--body-12-regular-font-size);
    letter-spacing: var(--body-12-regular-letter-spacing);
    line-height: var(--body-12-regular-line-height);
    white-space: nowrap;
    font-style: var(--body-12-regular-font-style);
  }
  
  .frame .text-wrapper-8 {
    position: relative;
    align-self: stretch;
    font-family: var(--body-16-regular-font-family);
    font-weight: var(--body-16-regular-font-weight);
    color: var(--textdefaultblack-000000);
    font-size: var(--body-16-regular-font-size);
    letter-spacing: var(--body-16-regular-letter-spacing);
    line-height: var(--body-16-regular-line-height);
    font-style: var(--body-16-regular-font-style);
  }
  
  .frame .icon-COPYME-wrapper {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    padding: 4px 0px;
    position: relative;
    flex: 0 0 auto;
  }
  
  .frame .div-11 {
    display: inline-flex;
    flex-direction: column;
    align-items: flex-start;
    position: relative;
    flex: 0 0 auto;
  }
  
  .frame .element-generic-arrow {
    position: relative;
    width: 16px;
    height: 16px;
  }
  
  .frame .button {
    display: flex;
    height: 56px;
    align-items: center;
    padding: 16px;
    position: relative;
    flex: 1;
    flex-grow: 1;
    background-color: var(--textdefaultwhite-ffffff);
    border-radius: 8px;
    border: 1px solid;
    border-color: var(--linedefault-dbdbdb);
  }
  
  .frame .horizontal-container {
    display: flex;
    flex-direction: column;
    width: 95px;
    align-items: flex-start;
    gap: 4px;
    position: relative;
  }
  
  .frame .text-wrapper-9 {
    position: relative;
    width: fit-content;
    margin-top: -1px;
    margin-right: -71px;
    font-family: var(--body-16-regular-font-family);
    font-weight: var(--body-16-regular-font-weight);
    color: var(--textlight-767676);
    font-size: var(--body-16-regular-font-size);
    letter-spacing: var(--body-16-regular-letter-spacing);
    line-height: var(--body-16-regular-line-height);
    white-space: nowrap;
    font-style: var(--body-16-regular-font-style);
  }
  
  .frame .text-wrapper-10 {
    position: relative;
    width: fit-content;
    margin-top: -1px;
    margin-right: -78px;
    font-family: var(--body-16-regular-font-family);
    font-weight: var(--body-16-regular-font-weight);
    color: var(--system-colorcritical-ea002a);
    font-size: var(--body-16-regular-font-size);
    letter-spacing: var(--body-16-regular-letter-spacing);
    line-height: var(--body-16-regular-line-height);
    white-space: nowrap;
    font-style: var(--body-16-regular-font-style);
  }
  
  .frame .checkbox-with-text {
    display: flex;
    align-items: flex-start;
    gap: 8px;
    padding: 8px 0px 0px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .checkbox {
    position: relative;
    width: 16px;
    height: 16px;
    background-color: var(--textsecondary-333333);
    border-radius: 4px;
  }
  
  .frame .tick {
    position: absolute;
    width: 10px;
    height: 10px;
    top: 3px;
    left: 3px;
  }
  
  .frame .div-12 {
    display: flex;
    align-items: flex-start;
    gap: 2px;
    position: relative;
    flex: 1;
    flex-grow: 1;
  }
  
  .frame .remember-the {
    position: relative;
    flex: 1;
    margin-top: -1px;
    font-family: var(--body-13-regular-font-family);
    font-weight: var(--body-13-regular-font-weight);
    color: #000000;
    font-size: var(--body-13-regular-font-size);
    letter-spacing: var(--body-13-regular-letter-spacing);
    line-height: var(--body-13-regular-line-height);
    font-style: var(--body-13-regular-font-style);
  }
  
  .frame .label {
    position: relative;
    width: fit-content;
    margin-top: -1px;
    text-shadow: 0px 0.5px 1.5px #00000080;
    font-family: "Syne-Regular", Helvetica;
    font-weight: 400;
    color: var(--color-circlecred-ea002a);
    font-size: 17px;
    letter-spacing: 0;
    line-height: 17px;
    white-space: nowrap;
  }
  
  .frame .span {
    font-family: var(--body-13-regular-font-family);
    font-weight: var(--body-13-regular-font-weight);
    color: #000000;
    font-size: var(--body-13-regular-font-size);
    letter-spacing: var(--body-13-regular-letter-spacing);
    line-height: var(--body-13-regular-line-height);
    font-style: var(--body-13-regular-font-style);
  }
  
  .frame .text-wrapper-11 {
    text-decoration: underline;
    font-family: var(--body-13-regular-font-family);
    font-style: var(--body-13-regular-font-style);
    font-weight: var(--body-13-regular-font-weight);
    letter-spacing: var(--body-13-regular-letter-spacing);
    line-height: var(--body-13-regular-line-height);
    font-size: var(--body-13-regular-font-size);
  }
  
  .frame .standard-button-wrapper {
    all: unset;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    padding: 16px 0px 8px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .standard-button {
    all: unset;
    box-sizing: border-box;
    display: flex;
    min-width: 80px;
    height: 50px;
    align-items: center;
    justify-content: center;
    gap: 8px;
    padding: 16px 24px;
    position: relative;
    align-self: stretch;
    width: 100%;
    background-color: var(--branded-color-reddefaultnew-ea002a);
    border-radius: 48px;
  }
  
  .frame .text {
    position: relative;
    width: fit-content;
    margin-top: -2px;
    font-family: var(--body-16-bold-font-family);
    font-weight: var(--body-16-bold-font-weight);
    color: var(--textdefaultwhite-ffffff);
    font-size: var(--body-16-bold-font-size);
    text-align: center;
    letter-spacing: var(--body-16-bold-letter-spacing);
    line-height: var(--body-16-bold-line-height);
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 1;
    -webkit-box-orient: vertical;
    font-style: var(--body-16-bold-font-style);
  }
  
  .frame .div-13 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 9px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .text-wrapper-12 {
    position: relative;
    align-self: stretch;
    margin-top: -1px;
    font-family: var(--body-13-regular-font-family);
    font-weight: var(--body-13-regular-font-weight);
    color: var(--lineamplifed-767676);
    font-size: var(--body-13-regular-font-size);
    letter-spacing: var(--body-13-regular-letter-spacing);
    line-height: var(--body-13-regular-line-height);
    font-style: var(--body-13-regular-font-style);
  }
  
  .frame .text-wrapper-13 {
    position: relative;
    align-self: stretch;
    font-family: var(--body-13-regular-font-family);
    font-weight: var(--body-13-regular-font-weight);
    color: var(--lineamplifed-767676);
    font-size: var(--body-13-regular-font-size);
    letter-spacing: var(--body-13-regular-letter-spacing);
    line-height: var(--body-13-regular-line-height);
    font-style: var(--body-13-regular-font-style);
  }
  
  .frame .bottom {
    position: relative;
    width: 343px;
    height: 199px;
    background-color: #ffffff;
  }
  
  .frame .text-2 {
    display: flex;
    flex-direction: column;
    width: 311px;
    align-items: center;
    gap: 16px;
    position: absolute;
    top: 72px;
    left: 16px;
  }
  
  .frame .row {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    position: relative;
    align-self: stretch;
    width: 100%;
    flex: 0 0 auto;
  }
  
  .frame .text-wrapper-14 {
    position: relative;
    width: fit-content;
    margin-top: -1px;
    font-family: var(--body-11-regular-font-family);
    font-weight: var(--body-11-regular-font-weight);
    color: var(--textlight-767676);
    font-size: var(--body-11-regular-font-size);
    text-align: center;
    letter-spacing: var(--body-11-regular-letter-spacing);
    line-height: var(--body-11-regular-line-height);
    white-space: nowrap;
    font-style: var(--body-11-regular-font-style);
  }
  
  .frame .ellipse {
    position: relative;
    width: 4px;
    height: 4px;
    background-color: var(--textlight-767676);
    border-radius: 2px;
  }
  
  .frame .text-wrapper-15 {
    position: relative;
    align-self: stretch;
    font-family: var(--body-12-regular-font-family);
    font-weight: var(--body-12-regular-font-weight);
    color: var(--textlight-767676);
    font-size: var(--body-12-regular-font-size);
    text-align: center;
    letter-spacing: var(--body-12-regular-letter-spacing);
    line-height: var(--body-12-regular-line-height);
    font-style: var(--body-12-regular-font-style);
  }
  
  .frame .group {
    position: absolute;
    width: 343px;
    height: 48px;
    top: 0;
    left: 0;
  }
  
  .frame .overlap-group {
    position: relative;
    height: 48px;
  }
  
  .frame .divider {
    position: absolute;
    width: 343px;
    height: 17px;
    top: 6px;
    left: 0;
  }
  
  .frame .logo-DFS {
    position: absolute;
    width: 48px;
    height: 48px;
    top: 0;
    left: 147px;
  }
/////////////////
:root {
    --branded-color-purpledefault-781556: rgba(120, 21, 86, 1);
    --textdefaultblack-000000: rgba(0, 0, 0, 1);
    --colorgrey80-333333: rgba(51, 51, 51, 1);
    --textlight-767676: rgba(118, 118, 118, 1);
    --system-colorcritical-ea002a: rgba(234, 0, 42, 1);
    --color-circlecred-ea002a: rgba(234, 0, 42, 1);
    --textdefaultwhite-ffffff: rgba(255, 255, 255, 1);
    --lineamplifed-767676: rgba(118, 118, 118, 1);
    --textsecondary-333333: rgba(51, 51, 51, 1);
    --branded-color-reddefaultnew-ea002a: rgba(234, 0, 42, 1);
    --backgroundlv1-ffffff: rgba(255, 255, 255, 1);
    --linedefault-dbdbdb: rgba(219, 219, 219, 1);
    --body-14-semibold-font-family: "Syne", Helvetica;
    --body-14-semibold-font-weight: 600;
    --body-14-semibold-font-size: 14px;
    --body-14-semibold-letter-spacing: 0px;
    --body-14-semibold-line-height: 18px;
    --body-14-semibold-font-style: normal;
    --title-20-semibold-font-family: "Syne", Helvetica;
    --title-20-semibold-font-weight: 600;
    --title-20-semibold-font-size: 20px;
    --title-20-semibold-letter-spacing: 0px;
    --title-20-semibold-line-height: 24px;
    --title-20-semibold-font-style: normal;
    --body-13-regular-font-family: "Syne", Helvetica;
    --body-13-regular-font-weight: 400;
    --body-13-regular-font-size: 13px;
    --body-13-regular-letter-spacing: 0px;
    --body-13-regular-line-height: 17px;
    --body-13-regular-font-style: normal;
    --body-16-semibold-font-family: "Syne", Helvetica;
    --body-16-semibold-font-weight: 600;
    --body-16-semibold-font-size: 16px;
    --body-16-semibold-letter-spacing: 0px;
    --body-16-semibold-line-height: 20px;
    --body-16-semibold-font-style: normal;
    --body-14-regular-font-family: "Syne", Helvetica;
    --body-14-regular-font-weight: 400;
    --body-14-regular-font-size: 14px;
    --body-14-regular-letter-spacing: 0px;
    --body-14-regular-line-height: 18px;
    --body-14-regular-font-style: normal;
    --body-16-regular-font-family: "Syne", Helvetica;
    --body-16-regular-font-weight: 400;
    --body-16-regular-font-size: 16px;
    --body-16-regular-letter-spacing: 0px;
    --body-16-regular-line-height: 20px;
    --body-16-regular-font-style: normal;
    --mob-body-XS-reg-10px-font-family: "Syne", Helvetica;
    --mob-body-XS-reg-10px-font-weight: 400;
    --mob-body-XS-reg-10px-font-size: 10px;
    --mob-body-XS-reg-10px-letter-spacing: 0.4px;
    --mob-body-XS-reg-10px-line-height: 129.99999523162842%;
    --mob-body-XS-reg-10px-font-style: normal;
    --body-12-regular-font-family: "Syne", Helvetica;
    --body-12-regular-font-weight: 400;
    --body-12-regular-font-size: 12px;
    --body-12-regular-letter-spacing: 0px;
    --body-12-regular-line-height: 16px;
    --body-12-regular-font-style: normal;
    --body-16-bold-font-family: "Syne", Helvetica;
    --body-16-bold-font-weight: 700;
    --body-16-bold-font-size: 16px;
    --body-16-bold-letter-spacing: 0px;
    --body-16-bold-line-height: 20px;
    --body-16-bold-font-style: normal;
    --body-11-regular-font-family: "Syne", Helvetica;
    --body-11-regular-font-weight: 400;
    --body-11-regular-font-size: 11px;
    --body-11-regular-letter-spacing: 0px;
    --body-11-regular-line-height: 15px;
    --body-11-regular-font-style: normal;
    --white-bg-shadow: 0px 2px 16px 0px rgba(0, 0, 0, 0.12);
  }
////////////////////
html,
body {
  padding: 0;
  margin: 0;
  font-family:
    -apple-system,
    BlinkMacSystemFont,
    Segoe UI,
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    Fira Sans,
    Droid Sans,
    Helvetica Neue,
    sans-serif;
  line-height: 1.6;
  font-size: 18px;
}

* {
  box-sizing: border-box;
}

a {
  color: #0070f3;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

img {
  max-width: 100%;
  display: block;
}
