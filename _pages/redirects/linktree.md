---
layout: page
title: Links
permalink: /links
comments: false
nosubscribe: true
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

<style>
    .links-container {
        max-width: 500px;
        margin: 0 auto;
    }
    .profile-section {
        text-align: center;
        margin-bottom: 3rem;
    }
    .profile-img {
        width: 100px;
        height: 100px;
        border-radius: 50%;
        margin-bottom: 1.5rem;
        filter: grayscale(20%);
    }
    .profile-name {
        color: #1a1a1a;
        font-size: 1.5rem;
        font-weight: 600;
        margin-bottom: 0.5rem !important;
        letter-spacing: -0.02em;
    }
    .profile-tagline {
        color: #0d6efd;
        font-size: 0.95rem;
        margin-bottom: 0;
        font-weight: 400;
    }
    .link-item {
        padding: 1rem 1.25rem;
        margin-bottom: 0.75rem;
        border-radius: 8px;
        border: 1px solid #022b82;
        background-color: white;
        text-decoration: none;
        color: #022b82;
        display: flex;
        align-items: center;
        justify-content: space-between;
        transition: all 0.2s ease;
    }
    .link-item:hover {
        background-color: #022b82;
        color: white;
        text-decoration: none;
        transform: translateY(-2px);
        box-shadow: 0 4px 8px rgba(13, 110, 253, 0.2);
    }
    .link-content {
        display: flex;
        align-items: center;
    }
    .link-icon {
        font-size: 1.25rem;
        margin-right: 1rem;
        color: #022b82;
        width: 24px;
        text-align: center;
    }
    .link-item:hover .link-icon {
        color: white;
    }
    .link-text {
        font-weight: 500;
        font-size: 1rem;
    }
    .link-arrow {
        font-size: 1rem;
        color: #022b82;
    }
    .link-item:hover .link-arrow {
        color: white;
        transform: translateX(4px);
    }
</style>

<div class="links-container">
    <div class="profile-section">
        <img src="https://avatars.githubusercontent.com/u/53946861" alt="Coach Rye" class="profile-img">
        <h1 class="profile-name">Coach Rye</h1>
        <p class="profile-tagline">Harness Your Strengths. Architect Your Success.</p>
    </div>

    <div class="links-section">
        <a href="/youtube" class="link-item">
            <div class="link-content">
                <i class="bi bi-youtube link-icon"></i>
                <span class="link-text">YouTube</span>
            </div>
            <i class="bi bi-arrow-right link-arrow"></i>
        </a>

        <a href="/pod" class="link-item">
            <div class="link-content">
                <i class="bi bi-mic-fill link-icon"></i>
                <span class="link-text">Podcast</span>
            </div>
            <i class="bi bi-arrow-right link-arrow"></i>
        </a>

        <a href="/blog" class="link-item">
            <div class="link-content">
                <i class="bi bi-journal-text link-icon"></i>
                <span class="link-text">Blog</span>
            </div>
            <i class="bi bi-arrow-right link-arrow"></i>
        </a>

        <a href="/li" class="link-item">
            <div class="link-content">
                <i class="bi bi-linkedin link-icon"></i>
                <span class="link-text">LinkedIn</span>
            </div>
            <i class="bi bi-arrow-right link-arrow"></i>
        </a>

        <a href="/fb" class="link-item">
            <div class="link-content">
                <i class="bi bi-facebook link-icon"></i>
                <span class="link-text">Facebook</span>
            </div>
            <i class="bi bi-arrow-right link-arrow"></i>
        </a>

        <a href="/ig" class="link-item">
            <div class="link-content">
                <i class="bi bi-instagram link-icon"></i>
                <span class="link-text">Instagram</span>
            </div>
            <i class="bi bi-arrow-right link-arrow"></i>
        </a>
    </div>
</div>