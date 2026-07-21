# Upwork proposal, ready to paste

**Job:** WordPress Website Content & Layout Update (Elementor)
**Job id:** ~022079522286316590798
**Apply URL:** https://www.upwork.com/nx/proposals/job/~022079522286316590798/apply/
**Live demo:** https://langeritch.github.io/roseland-house-demo/

---

## Form fields

| Field | Value |
|---|---|
| Payment | By project |
| Bid | $50 (matches the budget shown on the post; raise only if the apply page shows a higher budget) |
| Duration | Less than 1 month |
| Attachments | None needed, the demo is a live link |

Screening questions could not be read without opening the apply page. Answer each one
directly and briefly in the same voice, and never leave a required one blank.

---

## Cover letter

I built your updates as a live demo first: https://langeritch.github.io/roseland-house-demo/

It has the video landing section replacing the hero banner, your new six item menu, and the new Self-Catering page.

For the hero I used the same method mackayabella.co.za uses, an Elementor section with a self hosted background video set to autoplay, muted, looping and playing on mobile. Mine is under 1 MB so it does not slow the page, and the placeholder clip swaps straight out when your footage is ready.

The Self-Catering page is built from the four units on your current page, real copy and photos. It is a fast sample, 100% editable, so your revised homepage copy drops straight in.

Turnaround is 3 working days from receiving the copy, 2 if you need it sooner. Elementor and responsive WordPress are my day to day work, and the demo is fully responsive.

One question: your new menu drops Galleries and Blog. Keep those pages live and just remove them from the nav, or remove them completely?

More of my live work: santihaex.com

---

## Why this demo is on brief

The client asked for four specific changes to an existing Elementor site, not a redesign.
The demo delivers exactly those four, using their own brand, copy and photography:

1. **Homepage copy** rebuilt with their real verbatim copy, ready for the revised version.
2. **Navigation** set to exactly Home, About, Accommodation, Conference, Self-Catering, Contact.
3. **Self-Catering page** built from roseland.co.za/self-catering-accommodation, all four units.
4. **Video landing section** replacing the hero banner, matching the mackayabella technique.

## Reference detail worth knowing

mackayabella.co.za serves its hero through Elementor's hosted background video:

```
<video class="elementor-background-video-hosted" autoplay muted playsinline loop>
background_video_link: https://res.cloudinary.com/.../ac_none,q_40/v1680356066/Mkb_zvmtzs.mp4
background_video_start: 46
background_play_on_mobile: yes
```

So it is a self hosted MP4 on Cloudinary with audio stripped (`ac_none`) and quality
dropped to 40 for filesize, starting 46 seconds in. The demo mirrors that approach:
audio stripped, H.264 at CRF 28, plus a WebM fallback and a poster frame.

| Asset | Size |
|---|---|
| hero.webm | 579 KB |
| hero.mp4 | 993 KB |
| poster | 114 KB |

## Open question for the client

The requested menu drops **Galleries** and **Blog**, which both exist on the current site.
Worth confirming whether those pages stay live and just leave the nav, or get removed.
(The blog currently holds only the default "Hello world!" WordPress post.)
