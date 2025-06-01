---
layout: default
title: WhatsApp Bot Documentation
description: Comprehensive guide for building WhatsApp bots with modern web interface
toc: false
---

<div class="hero">
  <div class="container">
    <h1>🚀 WhatsApp Bot Documentation</h1>
    <p>Comprehensive guide for building powerful WhatsApp bots with ease</p>
    <div class="cta-buttons">
      <a href="#install" class="btn btn-primary">
        <i class="fas fa-rocket"></i>
        Get Started
      </a>
      <a href="https://github.com/username/repo-name" class="btn btn-secondary" target="_blank">
        <i class="fab fa-github"></i>
        View on GitHub
      </a>
    </div>
  </div>
</div>

<section class="features">
  <div class="container">
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-bolt"></i>
        </div>
        <h3>Easy Setup</h3>
        <p>Get started in minutes with our comprehensive installation guide and examples.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-cogs"></i>
        </div>
        <h3>Full Featured</h3>
        <p>Support for all WhatsApp features including media, groups, polls, and more.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-shield-alt"></i>
        </div>
        <h3>Secure & Reliable</h3>
        <p>Built with security in mind and battle-tested for production use.</p>
      </div>
    </div>
  </div>
</section>

<div class="container">
  <div class="content-wrapper">
    <article class="article full-width">
      <div class="article-content">
        <!-- Konten Manual dari README structure -->
        
        # Disclaimer
        This documentation provides comprehensive guide for WhatsApp bot implementation.
        
        ## Example
        Basic example of how to use the WhatsApp bot library.
        
        ## Install
        Installation guide and requirements for getting started.
        
        # Index
        
        ## Connecting Account
        Learn how to connect your WhatsApp account to the bot.
        
        ### Starting socket with **QR-CODE**
        Method 1: Using QR code for authentication.
        
        ### Starting socket with **Pairing Code**
        Method 2: Using pairing code for authentication.
        
        ### Receive Full History
        How to receive message history when connecting.
        
        ## Important Notes About Socket Config
        Configuration tips for optimal performance.
        
        ### Caching Group Metadata (Recommended)
        Improve performance by caching group information.
        
        ### Improve Retry System & Decrypt Poll Votes
        Enhanced reliability and poll support.
        
        ### Receive Notifications in Whatsapp App
        Enable notifications in your WhatsApp application.
        
        ## Saving & Restoring Sessions
        Manage user sessions effectively.
        
        ## Handling Events
        Process incoming messages and events.
        
        ### Example to Start
        Basic event handling examples.
        
        ### Decrypt Poll Votes
        Handle poll responses and voting.
        
        ### Summary of Events on First Connection
        What to expect on initial connection.
        
        ## Implementing a Data Store
        Persistent data storage solutions.
        
        ## Whatsapp IDs Explain
        Understanding WhatsApp ID formats.
        
        ## Utility Functions
        Helper functions for common tasks.
        
        ## Sending Messages
        Comprehensive message sending guide.
        
        ### Non-Media Messages
        Send text-based messages.
        
        #### Buttons Message
        Interactive button messages.
        
        #### Buttons Flow
        Multi-step button interactions.
        
        #### Interactive Message
        Rich interactive content.
        
        #### Text Message
        Simple text messaging.
        
        #### Quote Message (works with all types)
        Reply to existing messages.
        
        #### Mention User (works with most types)
        Tag users in messages.
        
        #### Mention Status
        Reference user status updates.
        
        #### Result Poll From Newsletter
        Poll results from newsletters.
        
        #### Send Album Message
        Multiple media in one message.
        
        #### Interactive Response
        Handle user interactions.
        
        #### Request Payment
        Payment request functionality.
        
        #### Event Message
        Calendar and event messages.
        
        #### Interactive
        Advanced interactive features.
        
        #### Forward Messages
        Forward existing messages.
        
        #### Location Message
        Share location data.
        
        #### Contact Message
        Share contact information.
        
        #### Reaction Message
        Add reactions to messages.
        
        #### Pin Message
        Pin important messages.
        
        #### Poll Message
        Create polls and surveys.
        
        ### Sending Messages with Link Previews
        Rich link previews in messages.
        
        ### Media Messages
        Send multimedia content.
        
        #### Gif Message
        Animated GIF support.
        
        #### Video Message
        Video file handling.
        
        #### Audio Message
        Voice and audio messages.
        
        #### Image Message
        Image sharing functionality.
        
        #### View Once Message
        Self-destructing media.
        
        ## Modify Messages
        Edit and manage existing messages.
        
        ### Deleting Messages (for everyone)
        Remove messages from chat.
        
        ### Editing Messages
        Modify sent messages.
        
        ## Manipulating Media Messages
        Advanced media handling.
        
        ### Thumbnail in Media Messages
        Generate and manage thumbnails.
        
        ### Downloading Media Messages
        Save received media files.
        
        ### Re-upload Media Message to Whatsapp
        Re-share media content.
        
        ## Reject Call
        Handle incoming calls.
        
        ## Send States in Chat
        Manage chat status indicators.
        
        ### Reading Messages
        Mark messages as read.
        
        ### Update Presence
        Show online/typing status.
        
        ## Modifying Chats
        Chat management features.
        
        ### Archive a Chat
        Archive conversations.
        
        ### Mute/Unmute a Chat
        Control notifications.
        
        ### Mark a Chat Read/Unread
        Manage read status.
        
        ### Delete a Message for Me
        Personal message deletion.
        
        ### Delete a Chat
        Remove entire conversations.
        
        ### Pin/Unpin a Chat
        Organize important chats.
        
        ### Star/Unstar a Message
        Bookmark messages.
        
        ### Disappearing Messages
        Self-destructing messages.
        
        ## User Querys
        Retrieve user information.
        
        ### Check If ID Exists in Whatsapp
        Validate WhatsApp accounts.
        
        ### Query Chat History (groups too)
        Access message history.
        
        ### Fetch Status
        Get user status updates.
        
        ### Fetch Profile Picture (groups too)
        Download profile images.
        
        ### Fetch Bussines Profile (such as description or category)
        Business account information.
        
        ### Fetch Someone's Presence (if they're typing or online)
        Real-time presence data.
        
        ## Change Profile
        Modify account settings.
        
        ### Change Profile Status
        Update status message.
        
        ### Change Profile Name
        Modify display name.
        
        ### Change Display Picture (groups too)
        Update profile photos.
        
        ### Remove display picture (groups too)
        Delete profile images.
        
        ## Groups
        Group chat management.
        
        ### Create a Group
        Start new group chats.
        
        ### Add/Remove or Demote/Promote
        Manage group members.
        
        ### Change Subject (name)
        Update group names.
        
        ### Change Description
        Modify group descriptions.
        
        ### Change Settings
        Configure group options.
        
        ### Leave a Group
        Exit group conversations.
        
        ### Get Invite Code
        Generate invitation links.
        
        ### Revoke Invite Code
        Invalidate invitation links.
        
        ### Join Using Invitation Code
        Join groups via links.
        
        ### Get Group Info by Invite Code
        Preview group information.
        
        ### Query Metadata (participants, name, description...)
        Retrieve group details.
        
        ### Join using `groupInviteMessage`
        Alternative joining method.
        
        ### Get Request Join List
        Manage join requests.
        
        ### Approve/Reject Request Join
        Handle membership requests.
        
        ### Get All Participating Groups Metadata
        List all groups.
        
        ### Toggle Ephemeral
        Enable disappearing messages.
        
        ### Change Add Mode
        Control who can add members.
        
        ## Privacy
        Privacy and security settings.
        
        ### Block/Unblock User
        Manage blocked contacts.
        
        ### Get Privacy Settings
        Review current settings.
        
        ### Get BlockList
        List blocked users.
        
        ### Update LastSeen Privacy
        Control visibility.
        
        ### Update Online Privacy
        Manage online status.
        
        ### Update Profile Picture Privacy
        Control photo visibility.
        
        ### Update Status Privacy
        Manage status visibility.
        
        ### Update Read Receipts Privacy
        Control read indicators.
        
        ### Update Groups Add Privacy
        Manage group additions.
        
        ### Update Default Disappearing Mode
        Set default message expiry.
        
        ## Broadcast Lists & Stories
        Mass messaging features.
        
        ### Send Broadcast & Stories
        Share content widely.
        
        ### Query a Broadcast List's Recipients & Name
        Manage broadcast lists.
        
        ## Writing Custom Functionality
        Advanced customization.
        
        ### Enabling Debug Level in Baileys Logs
        Debugging and troubleshooting.
        
        ### How Whatsapp Communicate With Us
        Understanding the protocol.
        
        ### Register a Callback for Websocket Events
        Custom event handling.
        
        ### NOTE
        Important notes and considerations.
        
      </div>
    </article>
  </div>
</div>