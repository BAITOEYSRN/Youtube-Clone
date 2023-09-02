<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Youtube Clone</title>

    <link rel="stylesheet" href="styles/header.css" />
    <link rel="stylesheet" href="styles/general.css" />
    <link rel="stylesheet" href="styles/video.css" />
    <link rel="stylesheet" href="styles/sidebar.css" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <header class="header">
      <div class="left-section">
        <img
          class="hamburger-menu"
          src="icons/hamburger-menu.svg"
          alt="hamburger-menu"
        />

        <img
          class="youtube-logo"
          src="icons/youtube-logo.svg"
          alt="youtube-logo"
        />
      </div>
      <div class="middle-section">
        <input class="search-bar" type="text" placeholder="Search" />
        <button class="search-button">
          <img class="search-icon" src="icons/search.svg" alt="search" />
          <div class="tooltip">Search</div>
        </button>
        <button class="voice-search-button">
          <img
            class="voice-search-icon"
            src="icons/voice-search-icon.svg"
            alt="voice-search-icon"
          />
          <div class="tooltip">Search with voice</div>
        </button>
      </div>
      <div class="right-section">
        <div class="upload-icon-container">
          <img class="upload-icon" src="icons/upload.svg" alt="upload" />
          <div class="tooltip">Create</div>
        </div>
        <div class="upload-icon-container">
          <img
            class="apps-icon"
            src="icons/youtube-apps.svg"
            alt="youtube-apps"
          />
          <div class="tooltip">Youtube apps</div>
        </div>
        <div class="upload-icon-container">
          <div class="notifications-icon-container">
            <img
              class="notifications-icon"
              src="icons/notifications.svg"
              alt="notifications"
            />
            <div class="notifications-count">3</div>
          </div>
          <div class="tooltip">Notifications</div>
        </div>
        <div class="upload-icon-container">
          <img
            class="current-user-picture"
            src="images/unnamed.jpg"
            alt="unnamed"
          />
        </div>
      </div>
    </header>

    <nav class="sidebar">
      <div class="sidebar-link">
        <img src="icons/home.svg" />
        <div>Home</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/explore.svg" />
        <div>Explore</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/subscriptions.svg" />
        <div>Subscriptions</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/originals.svg" />
        <div>Originals</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/youtube-music.svg" />
        <div>Youtube Music</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/library.svg" />
        <div>Library</div>
      </div>
    </nav>
    <man>
      <section class="video-grid">
        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/a4R36sCCZz8?si=so8CaFhY2X4lGYaY">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/a4R36sCCZz8/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLChyieCNrsDiLI-frfko42cBputRA"
              />
            </a>
            <div class="videos-time">4:19</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a
                href="https://www.youtube.com/channel/UC9mrIKAyV8AushabYK8i2ew"
              >
                <img
                  class="profile-picture"
                  src="https://yt3.googleusercontent.com/Vvj2zVZDOFjV8wEwkN5kZLnnbpcma_9KmA6xrfQE6Cv26FNOgSKachyYWrLXq1QkmmfF28C9=s176-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.googleusercontent.com/Vvj2zVZDOFjV8wEwkN5kZLnnbpcma_9KmA6xrfQE6Cv26FNOgSKachyYWrLXq1QkmmfF28C9=s176-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">4EVE</div>
                  <div>ผู้ติดตาม 8.75 แสน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                4EVE - สิ่งเล็กน้อย ( LESS IS MORE ) Prod. by URBOYTJ | Official
                MV
              </p>
              <p class="video-author">4EVE</p>
              <p class="video-stats">
                การดู 6,496,444 ครั้ง &#183; 1 ปีที่แล้ว
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a
              href="https://www.youtube.com/live/LZG_UfkzArg?si=sg0R9wDFD2RbjhI7"
            >
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/LZG_UfkzArg/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLBrdwUsbAaTuZXkdLSFLpCyZ53jOQ"
                alt=""
              />
            </a>

            <div class="videos-time">3:31:29</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@BrOwnii3z">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/ytc/AOPolaQ_bgKPMiRoRv_MVDhM4NNY9ErHS3RUHY9oJnOk0g=s68-c-k-c0x00ffffff-no-rj"
                />
              </a>
              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/ytc/AOPolaQ_bgKPMiRoRv_MVDhM4NNY9ErHS3RUHY9oJnOk0g=s68-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">BrOwnii3z</div>
                  <div>ผู้ติดตาม 1.28 แสน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                มาเชียร์น้องกล้า Watchparty Masters Tokyo day 8 let's GO
              </p>
              <p class="video-author">BrOwnii3z</p>
              <p class="video-stats">
                การดู 95,170 ครั้ง &#183; สตรีมแล้วเมื่อ 1 เดือนที่ผ่านมา 3
                ชั่วโมง และ 31 นาที
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/d_j6dAUInbI?si=AizdXUVB2g0X1sEo">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/d_j6dAUInbI/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLDBKVeByVDXVqmCnSkW7zkb5F12Fw"
                alt=""
              />
            </a>
            <div class="videos-time">4:38</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@DOORPLANT__">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/rFLfp2FRDdaad6XjhTb6g8WlXc19j2RgakQ__-XLWyTPu-5WdY92Ud4AteiO7BghQLq6QHqHBg=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>
              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/rFLfp2FRDdaad6XjhTb6g8WlXc19j2RgakQ__-XLWyTPu-5WdY92Ud4AteiO7BghQLq6QHqHBg=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">DOOR PLANT</div>
                  <div>ผู้ติดตาม 2.81 หมื่น คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">Door Plant - ขอให้เธอ (OFFICIAL MV)</p>
              <p class="video-author">DOOR PLANT</p>
              <p class="video-stats">การดู 3.6 แสน ครั้ง &#183; 3 ปีที่แล้ว</p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/N9bashij_7c?si=N99rh6ly5y7Mo_z4">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/N9bashij_7c/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLDQwMNiFiSR1Sa8rR0dRV47z8Z_jA"
                alt=""
              />
            </a>

            <div class="videos-time">4:22</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@whattheduckmusic">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/hS3Ij0SarMb2D9M7ADpQubY_rdjqqk06b_URN1KlOtJktAjRCe7eKXK_7Fvv3HpLF_WaHLtw=s68-c-k-c0x00ffffff-no-rj"
                />
              </a>
              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/hS3Ij0SarMb2D9M7ADpQubY_rdjqqk06b_URN1KlOtJktAjRCe7eKXK_7Fvv3HpLF_WaHLtw=s68-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">Whattheduck</div>
                  <div>ผู้ติดตาม 3.91 ล้าน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                LANDOKMAI - เพลงรักเพลงแรก (Blooming) [Official MV]
              </p>
              <p class="video-author">Whattheduck</p>
              <p class="video-stats">
                การดู 2.2 แสน ครั้ง &#183; 3 วันที่ผ่านมา
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/bKkN7iHkeXM?si=0QYZj0I1-59H8uNV">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/bKkN7iHkeXM/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLBJcO7EyMysJ7sSuNZ60ZJUOZ9pCg"
                alt=""
              />
            </a>

            <div class="videos-time">3:12</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@reinizra">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/-LdYrq6L89Fvi3MDtQzVtQtvkNfKIBXbmba2J84KKUm4-8QWqPSJqi_xNgBu2O-tuOmKxw9qPg=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/-LdYrq6L89Fvi3MDtQzVtQtvkNfKIBXbmba2J84KKUm4-8QWqPSJqi_xNgBu2O-tuOmKxw9qPg=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">เรนิษรา</div>
                  <div>ผู้ติดตาม 3.24 แสน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                เรนิษรา - ร้องไห้จนเบลอและเผลอลืมตัวเอง (Official Music Video)
              </p>
              <p class="video-author">เรนิษรา</p>
              <p class="video-stats">การดู 4.9 ล้าน ครั้ง &#183; 1 ปีที่แล้ว</p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/qUJArzfzVSo?si=HbyL2Nl_rBCEvvdY">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/qUJArzfzVSo/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLBZKMP5qm1AY583vc9frQfS8gFtng"
                alt=""
              />
            </a>

            <div class="videos-time">4:01</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@plasuiplasui9971">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/CUstkPElJHqB3T2FruXM1QbxToyZ7r27WuHifFacQcYZiQ-II_N1aBAhked1DrjU4aBehzVazw=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/CUstkPElJHqB3T2FruXM1QbxToyZ7r27WuHifFacQcYZiQ-II_N1aBAhked1DrjU4aBehzVazw=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">PLASUI PLASUI</div>
                  <div>ผู้ติดตาม 8.23 หมื่น คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                PLASUI PLASUI - อีกไม่นานก็เจอ (Lost and Found) [OFFICIAL MV]
              </p>
              <p class="video-author">PLASUI PLASUI</p>
              <p class="video-stats">การดู 7 แสน ครั้ง &#183; 3 ปีที่แล้ว</p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/TwpCimGy5eQ?si=E5WRD5Q9-iT7KSY3">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/tXGoj10MZVM/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLBj_iCEyu_0tqquxxqijjjUp11w2A"
                alt=""
              />
            </a>

            <div class="videos-time">4:35</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@AnatomyRabbit2">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/ytc/AOPolaTh5nHKYPe_OOwdFIZSRvzyjuaZzx8tRrZ9L9wGEw=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/ytc/AOPolaTh5nHKYPe_OOwdFIZSRvzyjuaZzx8tRrZ9L9wGEw=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">Anatomy Rabbit</div>
                  <div>ผู้ติดตาม 5.67 แสน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                ANATOMY RABBIT - ขอให้โลกนี้ใจดีกับเธอ Feat. Alien SAFEPLANET
                (Official Audio)
              </p>
              <p class="video-author">Anatomy Rabbit</p>
              <p class="video-stats">การดู 18 ล้าน ครั้ง &#183; 2 ปีที่แล้ว</p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/M1MbUOMXFBk?si=I7s3p94XS0clM0DL">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/M1MbUOMXFBk/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLBgNyW8qJAqMVh079lBbT8T67whAw"
                alt=""
              />
            </a>

            <div class="videos-time">3:22</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@urworldmusic">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/KWaG5-33Fm3feckRhirzl0CVRW-cS_rFbCNQ5hIHCf9-DX37xWN0Bhpg9LYsA5fgMAL63l-gAw=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/KWaG5-33Fm3feckRhirzl0CVRW-cS_rFbCNQ5hIHCf9-DX37xWN0Bhpg9LYsA5fgMAL63l-gAw=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">URWORLD</div>
                  <div>ผู้ติดตาม 8.97 หมื่น คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">Urworld - Home (Official Visualizer)</p>
              <p class="video-author">URWORLD</p>
              <p class="video-stats">
                การดู 590,828 ครั้ง &#183; 10 เดือนที่ผ่านมา
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/f_wpqBt7r4k?si=ICPqkSw_vAICHL-6">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/f_wpqBt7r4k/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLA2W1TDsg3Jf1WuDnvAc574HZ9ejA"
                alt=""
              />
            </a>

            <div class="videos-time">4:23</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@whattheduckmusic">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/hS3Ij0SarMb2D9M7ADpQubY_rdjqqk06b_URN1KlOtJktAjRCe7eKXK_7Fvv3HpLF_WaHLtw=s68-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/hS3Ij0SarMb2D9M7ADpQubY_rdjqqk06b_URN1KlOtJktAjRCe7eKXK_7Fvv3HpLF_WaHLtw=s68-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">Whattheduck</div>
                  <div>ผู้ติดตาม 3.91 ล้าน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                loserpop - ถ้าเขาดีกว่า (You'd Better Go) [Official MV]
              </p>
              <p class="video-author">Whattheduck</p>
              <p class="video-stats">
                การดู 1.1 แสน ครั้ง &#183; 8 วันที่ผ่านมา
              </p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/ow3dN47u0e0?si=-dBBRHlZGgrT7Ml9">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/fd5u47LH4RU/hqdefault.jpg?sqp=-oaymwEnCNACELwBSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLAY5U9DnHgsSih07oI7txhb2FU3jw"
                alt=""
              />
            </a>

            <div class="videos-time">4:56</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@plasticcavern">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/H36NHyQ7vtVGA2MxWa_gFeyr7Ow7e427y-g2g8G6AKI5UeogVKsftJovEebEELD2hxIXHdX1=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/H36NHyQ7vtVGA2MxWa_gFeyr7Ow7e427y-g2g8G6AKI5UeogVKsftJovEebEELD2hxIXHdX1=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">Plastic Cavern</div>
                  <div>ผู้ติดตาม 2.8 พัน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">อนันตกาล</p>
              <p class="video-author">Plastic Cavern - หัวข้อ</p>
              <p class="video-stats">การดู 1.3 แสน ครั้ง &#183; 1 ปีที่แล้ว</p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/erLvLQF6ROQ?si=5VkQZv7PWGUYqhZ-">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/erLvLQF6ROQ/hqdefault.jpg?sqp=-oaymwFBCNACELwBSFryq4qpAzMIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB8AEB-AH-CYAC0AWKAgwIABABGGUgZShlMA8=&rs=AOn4CLCyKqfjgRNRW_tfif3BuMPHxw8inA"
                alt=""
              />
            </a>
            <div class="videos-time">3:09</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@percy_2001">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/ROz42Ag5ViwAjQ27CjzEOwwBylR6mJUdZS4T93EzPs8guGX9E_gKq9bVn4HotTKsOTQZJ8gcig=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/ROz42Ag5ViwAjQ27CjzEOwwBylR6mJUdZS4T93EzPs8guGX9E_gKq9bVn4HotTKsOTQZJ8gcig=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">Percy</div>
                  <div>ผู้ติดตาม 6.08 หมื่น คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">
                Percy - Shall we feat. 4ourYou & GENA DESOUZA (Official Lyrics
                Video)
              </p>
              <p class="video-author">Percy</p>
              <p class="video-stats">
                การดู 6.8 ล้าน ครั้ง &#183; 2 สัปดาห์ที่ผ่านมา
              </p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnai-row">
            <a href="https://youtu.be/2yUD--XAnJg?si=paZuickxVBo3hm8d">
              <img
                class="wallpapers-vedio"
                src="https://i.ytimg.com/vi/2yUD--XAnJg/hqdefault.jpg?sqp=-oaymwEnCNACELwBSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGhACGAYgATgB&rs=AOn4CLCFt8_IfTZAyqIpb7eU9uxWKHPHHQ"
                alt=""
              />
            </a>

            <div class="videos-time">4:44</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <a href="https://www.youtube.com/@purpeech">
                <img
                  class="profile-picture"
                  src="https://yt3.ggpht.com/v3FAtLxhTYoUhgjH-JGfhTAsqqg_rVx9Rau5lpuzTz-VuZ-M7jzdrdZEYPShmpdgvbD3pGUYgHA=s88-c-k-c0x00ffffff-no-rj"
                />
              </a>

              <div class="box-channel">
                <div class="box-profile-picture">
                  <img
                    class="box-profile-picture"
                    src="https://yt3.ggpht.com/v3FAtLxhTYoUhgjH-JGfhTAsqqg_rVx9Rau5lpuzTz-VuZ-M7jzdrdZEYPShmpdgvbD3pGUYgHA=s88-c-k-c0x00ffffff-no-rj"
                  />
                </div>
                <div class="box-channel-title">
                  <div class="name-channel">PURPEECH Official</div>
                  <div>ผู้ติดตาม 2.56 แสน คน</div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <p class="video-title">อาจเป็นเพราะฉันเอง (me.)</p>
              <p class="video-author">PURPEECH Official</p>
              <p class="video-stats">
                การดู 4.6 ล้าน ครั้ง &#183; 4 เดือนที่ผ่านมา
              </p>
            </div>
          </div>
        </div>
      </section>
    </man>
  </body>
</html>
